![GA_Logo](../assets/ga.png)

## Resources

##Cheat Sheet



###Command Line Basics
The terminal (command prompt on Windows) is the developer way of navigating your computer. You are probably used to using the graphical interface provided (Finder on a mac and MyComputer on Windows).

Here is a quick reference for some of the most common commands you will use in this class. 
Remember when you see ```“$”``` or ```“C:\>”``` in these notes that is the prompt, don’t type it.

 		$  MAC
		C:\>  WINDOWS
####Navigation


How do I get into a folder?

  		$cd folder_name
		C:\> cd folder_name


How do I get to the parent folder?

		$cd ..
		C:\> cd ..

How do I see what is in the folder?

		$ls
		C:\> dir


How do I know what folder I am in?

		$pwd
		C:\> cd

How do I create a new folder?

		$mkdir folder_name
		C:\> mkdir folder_name


####Deleting - (Proceed With Caution)

How do I delete a folder?

		$rm -r folder_name
		c:\> rmdir folder-name

How do I delete a file?
		
		$rm -f file_name
		C:\> del file_name

How do I move a file?

		$mv file_name folder_name
		C:\> move file_name folder_name
The file is removed from the old location and moved to the new one.

You can rename a file the same way

		$mv old_name new_name
		C:\> move old_name new_names


###Tips, Tricks & Motivation

__How is my instructor moving so fast?__

We hire wizards from Hogwarts to teach our courses. Just kidding they’re using shortcuts in the command line. 

Here are some to help you keep up:

**Tab Completion**: Press Tab to complete folder and file names                                                       

**Control + a**: Go to the beginning of the line                                                                      

**Control + e**: Go the the end of the line                                                                      

**Option + b**: Move back one word

**Option + f**: Move forward one word

**Up/Down Arrow Keys**: Repeats previous commands                                                               

**Control + w**: Delete last word typed

**Control + u**: Delete last line typed

**Control + y**: Paste last deleted item

**Control + l**: Clear the screen


----

### Variables, Conditionals and Methods



__Variables__


```ruby
 real_name = "Bruce Wayne"
 secret_identity = "Batman"
```

*String interpolation aka Adding Variables to String*

```ruby
puts "We just spilled the beans #{real_name} is #{secret_identity}"
```

> We just spilled the beans Bruce Wayne is Batman

__Arithmetic Operators__

| Operator | Description | Example (a = 4 and b = 2) | Output |
| ------------- |:-------------| :-----|:-----|
| ```+```      | Addition (add left to right, give result) |  ```puts a + b```  | 6 |
| ```-```      |  Subtraction (subtract left from right, give result)    |  ```puts a - b```  | 2 |
| ```*``` | Multiplication (multiply left by right, give result)   | ```puts a * b```  | 8 |
| ```/``` | Division (divide left by right, give result)  | ```puts a / b``` | 2 |
| ```%``` | Modulus (divide left by right, give remainder) | ```puts a % b```  | 0 |
| ```**``` |Exponent (multiply left by left, right times, give result)  | ```puts a ** b``` | 16 |


__Conditionals Operators__

| Operator        | Description  | Example         (a = 4 and b = 2)  | Evaluated As |
| -------------   |:-------------| :-----|:-----|
| == | Equality |  a == b | false |
| != |  Not Equal | a != b | true  |
| >  | Greater than | a > b | true  |
| < | Less than |a < b | true  |
| >= |Greater than  or equal to | a <= b | false |
| <= |Less than or equal to | a <= b | false |
| <=> |Same value? return 0, less than? return -1, greater than? return 1 | a <=> b | 1 |
| .eql? | same value and same type?| 1.eql?(1.0)| false |


__If Syntax__

```ruby
if (condition)
  code to execute if the condition is true
end
```

```ruby
if var == 20
   puts "Variable is 20"
end
```

__If Else Syntax__

```ruby
if var == 20
   puts "Variable is 20"
else
   puts "Variable is another number"
end
```

__If Else If Syntax__

```ruby
if var == 20
   print "Variable is 20"
elsif var == 30
   print "Variable is 30"
else
   print "Variable is something else"
end
```

__Methods__

__Simple Methods__

```ruby
def method_name
end
```

__Method w/ Parameters__

```ruby
def say (something)
      puts "They said #{something}"
end

 say ("Hello")

=> They said Hello
```

__Running .rb from the terminal__

```
	ruby file_name.rb
```

###Tips, Tricks and Motivation

- What is Programming [video](http://www.youtube.com/watch?v=YCDTYlUWkQE)
- Using Sublime Text 2 [video tutorial](https://tutsplus.com/course/improve-workflow-in-sublime-text-2/)
- [Tricked Out Sublime Text](http://net.tutsplus.com/tutorials/tools-and-tips/sublime-text-2-tips-and-tricks/)
-	[Learning to Program](http://worrydream.com/LearnableProgramming/)


###Still Feel Lost? 
####Catch Up With These Resources

- Intro to Ruby [tutorial](http://www.codeschool.com/courses/try-ruby) from Code School for beginners to wrap your head around programming concepts.
- Beginner Ruby [Tutorial](- http://www.codecademy.com/courses/ruby-beginner-en-d1Ylq?curriculum_id=5059f8619189a5000201fbcb)
- Book [chapter](http://ruby.bastardsbook.com/chapters/ifelse/) on conditionals.
- [Article](http://ruby.about.com/od/control/a/Conditional-Statements.htm) from about.com about ruby conditional statements.
- [Article](http://strugglingwithruby.blogspot.com/2008/11/conditional-statements.html) - More about true and false.
- [Khan academy tutorial](https://www.khanacademy.org/math/geometry/logical-reasoning/e/conditional_statements_and_truth_value) about logical reasoning.

 -----      
 