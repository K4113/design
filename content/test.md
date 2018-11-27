---
views:
    kursrepo:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo

    redovisa:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa
    byline:
        region: main
        template: anax/v2/block/default
        sort: 2
        data:
            meta:
                type: single
                route: block/byline
---
Test
=========================

+ Hello
+ Test
+ Testing

Cool!

*****


    lorem Lorem ipsum dolor sit amet

- - -

This is [a link](http://dbwebb.se/ "Title") to dbwebb.

1988.\ was Fredrik born.

1988. was fredrik born.

<div class="footer">
        &copy; 2018 Fredrik Nelsson
    </div>

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.

> This is the first level of quoting.
>
> > This is nested blockquote.
> >
> > > This is next blockquote.
>
> Back to the first level.
