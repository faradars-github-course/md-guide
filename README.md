<h1 id="top-doc">Markdown Guide</h1>

# Heading

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

# Menu

- Menu Part 1
- Menu Part 2
  - Item 2.1
  - Item 2.2
    - Item 2.2.1
    - Item 2.2.2
  - Item 2.3
- Menu Part 3

<ul>
    <li>Second Menu Part 1</li>
    <li>Second Menu Part 2
        <ul>
            <li>Second Menu Item 1</li>
            <li>Second Menu Item 2
                <ul>
                    <li>Second Menu Part 2.1</li>
                </ul>
            </li>
        </ul>
    </li>
    <li>Second Menu Part 3</li>
</ul>

1. Third Menu Part 1
2. Third Menu Part 2
   1. Third Menu Part 2.1
      1. Third Menu Part 2.1.1
      2. Third Menu Part 2.1.2
   2. Third Menu Part 2.2
3. Third Menu Part 3

---

# Highlight

- You Can Use ``For`Highlight`

- You Can Add Italic Text With " * " or " _ " Like : *Italic Text* and _Italic Text_

- You Can Add Bold Text With " ** " or " __ " Like : **Bold Text** and **Bold Text**

- You Can Add Bold And Italic Same With " *** " or " ___ " Like : ***Bold and Italic Text*** and ___Bold and Italic Text___

- You Can Use `diff` with `diff `. Example :

```diff
+    Add This Line

-    Remove This Line
```

- You Can Write Codes with ```. Example :

```javascript
console.log('Hello World');
```

- You Can Add Quote With >. Example :

> Hi There. Im `Mohammad Zolghadr`

- You Can Add NestedQuote With >>. Example

> Hi There
>
> > Im `Mohammad Zolghadr`

---

# Links and Images

- Images

![github in Faradars](https://faradars.org/wp-content/uploads/2023/03/04/640370c6ae4eb-fvpub164-png.png)

- Links

  - First : [Link Text](https://faradars.org/)

  - Second : <a href="https://faradars.org">Link Text</a>

  - Third : 

    [variable_link_name]:https://faradars.org
    [Go To My Site][variable_link_name]

- Image Link

[![github in Faradars](https://faradars.org/wp-content/uploads/2023/03/04/640370c6ae4eb-fvpub164-png.png)](https://faradars.org)


- Link To Some Part Of Document

<a href="#top-doc">Go To Top</a>

---

# Details and Summary

<ul>
  <li>
    <details>
      <summary>Item Title</summary>
      <ul>
        <li>
          <details>
            <summary>Menu 2</summary>
            <ul>
              <li>Menu 2.1</li>
              <li>Menu 2.2</li>
            </ul>
          </details>
        </li>
      </ul>
    </details>
  </li>
</ul>

---


# Table

| Col 1 | Col 2 | Col 3 |
|--|--|--|
|First Col Detail | Second Col Detail | Third Col Detail |
|First Col Detail | Second Col Detail | Third Col Detail |
|First Col Detail | Second Col Detail | Third Col Detail |
|First Col Detail | Second Col Detail | Third Col Detail |
|First Col Detail | Second Col Detail | Third Col Detail |
