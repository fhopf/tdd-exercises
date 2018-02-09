# TDD Exercises

There are lots of Katas available but sometimes even very simple exercises can be enough to practice the basics of TDD. 

## Some random exercises for practicing minimal steps:

* Create a method that accepts a String and returns an array or list of the words in the String (everything separated by whitespace)
** `"I am hungry"` returns `["I", "am", "hungry"]`
** Extension: Only return the first 5 words
** Extension: Only return unique words
* Create a method that accepts an array or list of Strings. Return an array/list that is sorted by length
** `["satu", "dua", "empat"]` is returned as `["dua", "satu", "empat"]` 
* Create a method that accepts an array/list of Strings and returns the size of the largest String
** `["satu", "dua", "empat"]` returns `5`, the length of the largest word `"empat"`
* Create a method that calculates the sum/product of all numbers given in a comma separated string
** `"1,2,3,4"` returns `10` for sum and `24` for product 
* For a class Product create a ProductValidator that returns true if the product is valid (has a name and a price).
** `{'name': 'Ayam Geprek', 'price': '25000.00'}` is valid but `{}`, `{'name': 'Soto Ayam'}` and `{'price': '20000.00'}` are not.
* Create a method that gets passed in an array/list of products. Calculate the max price, the min price and the sum.
* Create a method that gets passed in an array/list of products. Return an array/list of all the prices.
* Create a service that accepts a product and writes the JSON representation to a file.

## Mocking exercises:

* Create a Service that gets passed in firstname and lastname and persists a Person object in PersonRepository if both of them are set 
* Create a Service that gets passed in a comma separated string of names, each of those names should be sent to a Message Queue representation

## Katas (there are a lot more of course):

* [String Calculator](http://osherove.com/tdd-kata-1/)
* [Numbers in words](http://codingdojo.org/kata/NumbersInWords/)
* [Roman Numerals](http://codingdojo.org/kata/RomanNumerals/)


