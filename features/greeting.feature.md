# Feature: Greeting

This is about actually staying alive,
not the [Bee Gees song](https://www.youtube.com/watch?v=I_izvAbhExY).

## Rule: If you don't eat you die

![xkcd](https://imgs.xkcd.com/comics/lunch_2x.png)

`@important` `@essential`

### Scenario Outline: Say hello

- When the greeter says hello
- Then I should have heard "hello"

### Scenario Outline: Say foo

- When the greeter says foo foo
- Then I should have heard "foo"

### Scenario Outline: Say fooOO

- When the greeter says foo fooOO
- Then I should have heard "foo"
