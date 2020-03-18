Xpath
=======
```
"//button[contains(@class, 'class_name') and contains(@title, 'title')]"

//button[contains(text(), 'content')]
```

### XPath Axes
+ attribute: all attributes of the current node

```shell
//a[contains(@class, 'back-to-top')]/ancestor::div[contains(@class, 'node')]

//a[contains(@class, 'back-to-top')][1]/attribute::class # class is an object

```
+ ancestor
+ following-sibling (nhung thang cung bac truoc va sau current node)
+ descendant
+ ...

```
cssSelector("div[class*='class_name'][title='title']")
```

### Predicates
```
/bookstore/book[1]
/bookstore/book[price>35000]
/bookstore/book[position()<3]
# select first two book elements that are children of bookstore element
/bookstore/book[@lang and @index] # lang attribute exists

```

node vs element
