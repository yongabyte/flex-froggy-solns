# flex-froggy-solns


## Notes on flexbox from froggy


### Justify-Content
l1 - l4

### alighn-items
>- flex-start: Items align to the top of the container.
>- flex-end: Items align to the bottom of the container.
>- center: Items align at the vertical center of the container.
>- baseline: Items display at the [baseline](https://stackoverflow.com/questions/32551291/in-css-flexbox-why-are-there-no-justify-items-and-justify-self-properties) [of](https://stackoverflow.com/questions/34606879/whats-the-difference-between-flex-start-and-baseline) the container.
>- stretch: Items are stretched to fit the container.

### Flex Direction
>    - row: Items are placed the same as the text direction.
>    - row-reverse: Items are placed opposite to the text direction.
>    - column: Items are placed top to bottom.
>    - column-reverse: Items are placed bottom to top.

> when you set the direction to a reversed row or column, start and end are also reversed.

### Order

Unlike the properties that we have seen, `order` is applied to the individual items.
If `order` has not been set, the default value is zero.
< 0: move to the front;
> 0: move to the back;

### align-self
Similar to align-items, but on a individual item.

### flex-wrap

> - nowrap: squeezed all the items into a single line
> - wrap: allows items to be wrapped to additional lines
> - wrap-reverse: wrap but in reverse
