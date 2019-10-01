# **WHAT I LEARNED IN  WEEK 3** 


## `MORE HUMAN RESOURCES`

The frustration of Human Resources continued. Most definitely struggled with certain problems but brain is starting to get adjusted to a new way of thinking (I hope). 

    I feel proud as I completed the Countdown problem without any help!

___

## `RETURN OF THE STRING!`

Top quality activity which gave me a banging headache afterwards. An activity to be done again to reinforce how strings operate. This activity got me thinking about how strings operate and how to target certain elements. 

    function initials(str) {
    return firstCharacter(str) + '.' + str[str.indexOf(' ')+1] + '.';
    }

Colin showed us there were multiple ways of doing the same thing. This consolidated my understanding of certain concepts. 

    function yeller(str) {
    const capitalized = capitalize(str);
    const first = exclaim(capitalized);
    const second = exclaim(first);
    const third = exclaim(second);
    return third;
    }

    function yeller(str) {
        return capitalize(exclaim(exclaim(exclaim(str))));
    }

___

## `FUNCTIONS WITH PARAMETERS`

    let greeting = 'HEY';

    function yellAt(str) {
    greeting = greeting + ',' + ' ' + str + '!';
    }

Getting my head round using a previous variable declared and applying it within a function like above. It's smart to use variables previously declared as it gives us more flexibility to make changes. 

___

## `RETURN VALUES`

Understanding the parameters that we declare within our function give us the input and the **return** value provides us with the output. When the return statement is reached the function will stop executing. 

## `MAKING BASIC APPS`

I really enjoyed making the celsius to fahrenheit (and vice versa) converted through the terminal. Very excited to learn more about this kind of thing! 

I applied the same method and make my own kg to lbs converted (and vice versa).

    function toKg (pounds) {
        const kg = 0.453592 * pounds;
        console.log(kg);
    }

    const userInput = process.argv[2];

    toKg(userInput);

    function toPounds(kg) {
        const pounds = 2.20462 * kg
        console.log(pounds);
    }

    const userInput = process.argv[2];

    toPounds(userInput);

It was a great feeling witnessing the userInput work in the terminal and it being functional. 










