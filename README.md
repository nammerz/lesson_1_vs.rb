lesson_1_vs.rb
==============
#Lesson 1 Variable Scope
#1.1

a = 5
new_name = a + 5
puts new_name

some_method = [1, 1, 2, 2, 3, 3, 4, 4, 5, 5]
some_method.uniq
puts some_method

another_one = [6, 6, 7, 7, 8, 8, 9, 9, 10, 10]
another_one.uniq!
puts another_one

#1.2

numbers = 1
3.times do
numbers += 1
num = numbers
end
p numbers

