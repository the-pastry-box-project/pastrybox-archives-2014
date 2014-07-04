

This is the most important advice I can give to a programmer. *Code to an interface*. It’s a very important
concept that is difficult for new programmers to understand. An interface is a contract between my code and
your code that states, “if your code provides these methods with these arguments, my code will use your code
and do this.” My code does not care __how__ your code does what it does so long as your code provides the
methods and method arguments that my code expects.

## My code

I’ve written some code that contains a group of characters and asks each character to say
hello.

	<?phpclass Meeting{    protected $characters = array();    public function
	addCharacter(Introducible $character)    {        $this->characters[] = $character;    }    public function
	startIntroductions()    {        foreach ($this->characters as $character) {           
	$character->sayHello();        }    }}

My code provides a `addCharacter()` method that accepts one argument. The argument must implement this
`Introducible` interface.

	<?phpinterface Introducible{    public function
	sayHello();}

## Your code

You decide to create three characters. The first character is named Calvin.

	<?phpclass Calvin
	implements Introducible{    public function sayHello()    {        $this->putOnMask();       
	$this->putOnCape();        echo 'I am STUPENDOUS MAN!';        $this->runOutOfClassroom();   
	}}

The second character is named Wilson.

	class Wilson implements Introducible{    public function
	sayHello()    {        $this->putOnCap();        $this->peekOverFence();        echo 'Well hidey-ho
	good neighbor!';    }}

The third character is an HTTP server.

	class Server implements Introducible{    public function
	sayHello()    {        $this->boot();        $this->getRequest();        echo 'HTTP/1.1 418
	I'm a teapot';    }}

## Our code

Calvin, Wilson, and the Server are different classes that introduce themselves in drastically different ways.
All, however, implement the `Introducible` interface and are therefore compatible with my `Meeting`
object.

	<?php// Your code$calvin = new Calvin();$wilson = new Wilson();$server = new
	Server();// My code$meeting = new
	Meeting();$meeting->addCharacter($calvin);$meeting->addCharacter($wilson);$meeting->addCharacter($server);$meeting->startIntroductions();

Coding to an interface makes code extensible and delegates implementation details to otherwise unrelated code
written by other developers. Interfaces allow two or more otherwise unrelated objects to communicate with each
other. For example, anyone can create a character for my `Meeting` class. I don’t care what the character
is, how the character is coded, or what the character can do. All I require is that the character be able to
say hello by implementing the `Introducible` interface.