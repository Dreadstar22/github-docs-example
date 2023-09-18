# Writing Good Documentation
This document is for the Terraform Bootcamp. 

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible. 

Because it allows others to copy and paste their code to replicate or research issues. 

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with single quotations (')
  
```def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
num = gets.chomp.to_i

if num < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(num)
  puts "The factorial of #{num} is #{result}."
end
```

- When you can you should attempt to apply syntac highlighting to your codeblocks.

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
num = gets.chomp.to_i

if num < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(num)
  puts "The factorial of #{num} is #{result}."
end
```

![desktop-wallpaper-cool-tech-background-best-technology](https://github.com/Dreadstar22/github-docs-example/assets/66575153/764368aa-70a8-4e7f-9b5b-e840c5f17969)

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
  example.rb:2:in `<main>': undefined local variable or method `undefined_variable' for main:Object (NameError)
Did you mean?  defined?
```
> Here is an example of using a codeblock for an error that appers in bash.

## Step 3 - Use Github Flavored Task Lists

Github extends Markdown to have a list where you can check off items.[<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finsih Step 2
- [x] Finish Step 3

# Step 4 - Use Emoji's

Github Flavored Markdown(GFM) supports emoji shortcodes.

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud With Lightning | `cloud_with_lightning` | 🌩️ |
| Space Invader | `:space_invader:` | :space_invader: |

# Step 5 - how to create a table

You can use the following markdown format to create tables:
```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud With Lightning | `cloud_with_lightning` | 🌩️ |
| Space Invader | `:space_invader:` | :space_invader: |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options.[<sup>[2]</sup>](#external-references)

## External References

- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-)<sup>[2]</sup>
