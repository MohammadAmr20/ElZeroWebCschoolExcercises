# Lesson13 : Grouping Multiple Selectors :-

We can give common styles to elements by grouping them using "," 

for example we have 2 divs with classes "div1" "div2" and they have common styles like padding and margin so the syntax will be like that :

.div1,.div2{
    padding: 20px;
    margin: 10px;
}

we can group elements with classes like p , span etc.. .

# Lesson14 : Nesting :-

It's Useful when we want to select element that has a specific parent we know before.

div p{

}
It selects all paragraphs that is inside a div in the document .

We can select by id or class also.

div .special{

}

It selects all elements with id "special" that is inside a div in the document .


# Lesson15 : Dimensions Width and Height :-

## Attributes :
min-width: set the element  a specific width that won't be less than it.

max-width: set the element  a specific width that won't be greater than it.

The above attributes are same for height also.

width: fit-content will just preserve a share of space that barely hold the content not more no less.


# Lesson16 : OverFlow :-

As it's name , when there is overflow in content of element we can control it whether we hide it or make it scroll-able , we can control also the direction of overflow(horizontal or vertical).

## Values
1. visible : which is the default one .
2. hidden : which hides the overflowed content .
3. scroll : which make the overflowed part accesible by scrolling.
4. auto : depending on the situation , it chooses the best value whether visible or scroll of the content overflowed .