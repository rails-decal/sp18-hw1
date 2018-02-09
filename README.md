# Rails DeCal Spring 2018 Homework 1
This assignment involves writing scripts in Ruby to help you become familiar with the Ruby programming language.

**After forking this repository**, follow these commands to get started:
```
git clone https://github.com/your_username/sp18-hw1
cd sp18-hw1
```

## Q1
There is a method called `squared_sum` in hw1.rb. `squared_sum` accepts two integer parameters a and b. The method should calculate the sum of a and b and then return the square of the sum. Please finish this method.

## Q2
There is a method called `sort_array_plus_one` in hw1.rb. `sort_array_plus_one` accepts an array of integers as its parameter. The method should sort the given array, increment each element by 1, and finally return it. Please finish this method, either in a destructive or non-destructive fashion.

## Q3
There is a method called `combine_name` in hw1.rb. `combine_name` accepts two string parameters first_name and last_name. The method should return the first_name concatenated with the last_name with a space in between. Please finish this method.

Example:
```ruby
combine_name 'Nhi', 'Quach'
 => 'Nhi Quach'
```

## Q4
It's blockin' time!

In hw1.rb we defined a function called `blockin_time` that requires the foobar.rb file, and then calls a class method 'baz' from the Foobar class.

If you take a look at foobar.rb, you'll see that we've defined Foobar. Write a class function in foobar.rb called `baz` that accepts an array of integers as strings, changes each string into an integer, adds two to each number, keeps the even numbers only, removes any duplicates, rejects the resulting numbers greater than or equal to ten, and finally returns the sum of the resulting array.

For example:

`['1', '2', '3', '4', '5', '10']` returns 10. ((2+2) + (4+2)) = 10.

`['1', '2', '2', '2', '3', '4', '5', '10']` returns 10 as well.

## Q5
You want to get a leg up on your next Scrabble game with your grandmother. Write a function that takes a word (string) and returns the scrabble value of that word. Use the hash provided in the method to get the values. Assume the word has all lowercase letters.

Your code should be on a single line.

Hint: Try to split the word to get the letters in an array

Hint: Are `:this_one` and `"this_one"` equivalent objects?

Hint: Look at `Array#sum`

Example:
```
> scrabble("equestrian")
=> 19
```

This should get you familiar with basic operators, strings, symbols, and
iterators.

## Challenges
- Q1-Q3 can be written in 1 line and under 40 characters. Do this if you want an extra challenge.

- Check out the autograder.rb file and try to figure out how it works!

## Hints
- For Q2 check out these [docs about arrays](http://ruby-doc.org/core-2.2.0/Array.html). In web development in general, there are a lot of docs available when learning new libraries.

- For Q3 you might want to check out
[Ruby's string interpolation](https://en.wikipedia.org/wiki/String_interpolation#Ruby).

- To open the ruby interpreter to help debug call the 'irb' command in your terminal with the hw1.rb file.
```
irb hw1.rb
```

## How to check your answers
In the base directory of this repo, run `ruby autograder.rb`.
```
ruby autograder.rb
```

If `'All functions work'` appears, everything is correct!

## How to submit
You're done! Whew. Time to submit! Run these commands:

```
git add .
git commit -am "whatever message you want"
git push origin master
```

Fill out the submission form for this homework, which can be found on Piazza.
