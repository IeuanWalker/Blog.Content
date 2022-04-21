| Key | Value |
|---|---- |
| DatePosted | 2022-04-21 16:30:00.0000000 |
| Title | Complete markdown test |
| Summary | Tesing different markdown |
| FeatureImage | /Example.gif |
| KeyWords | markdown, test |
| CommentsId | 3 |


# H1 header
## H2 header
### H3 header

---

**Bold text**

---

*Italicized text*

---

> Block quote

---

Ordered list
1. First item
2. Second item
3. Third item
4. Fourth item

---

Unordered list
- First item
- Second item
- Third item
- Fourth item

---

Code

`Small code string`

```csharp
using System;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");    
    }
  }
}
```

```xml
<ContentPage xmlns="http://xamarin.com/schemas/2014/forms"
             xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
             xmlns:local="clr-namespace:XamlSamples"
             x:Class="XamlSamples.MainPage">

    <StackLayout>
        <!-- Place new controls here -->
        <Label Text="Welcome to Xamarin Forms!"
               VerticalOptions="Center"
               HorizontalOptions="Center" />
    </StackLayout>

</ContentPage>
```

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>

<p>My first paragraph.</p>
  
<p id="demo">JavaScript can change HTML content.</p>

<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button>

</body>
</html>
```

```js
// program to check the number of occurrence of a character

function countString(str, letter) {
    let count = 0;

    // looping through the items
    for (let i = 0; i < str.length; i++) {

        // check if the character is at that position
        if (str.charAt(i) == letter) {
            count += 1;
        }
    }
    return count;
}

// take input from the user
const string = prompt('Enter a string: ');
const letterToCheck = prompt('Enter a letter to check: ');

//passing parameters and calling the function
const result = countString(string, letterToCheck);

// displaying the result
console.log(result);
```

```css
body {
  font: 100% Helvetica, sans-serif;
  color: #333;
}
```

```scss
$font-stack: Helvetica, sans-serif;
$primary-color: #333;

body {
  font: 100% $font-stack;
  color: $primary-color;
}
```

```json
{
    "glossary": {
        "title": "example glossary",
		"GlossDiv": {
            "title": "S",
			"GlossList": {
                "GlossEntry": {
                    "ID": "SGML",
					"SortAs": "SGML",
					"GlossTerm": "Standard Generalized Markup Language",
					"Acronym": "SGML",
					"Abbrev": "ISO 8879:1986",
					"GlossDef": {
                        "para": "A meta-markup language, used to create markup languages such as DocBook.",
						"GlossSeeAlso": ["GML", "XML"]
                    },
					"GlossSee": "markup"
                }
            }
        }
    }
}
```

```sql
SELECT column1, column2 FROM table
WHERE column1='value'
```


```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


---

[Test link 1](https://ieuanwalker.com)
[Test link 2](https://github.com/IeuanWalker)

---

![image 1](https://pbs.twimg.com/profile_images/821849411991044096/lQFa_Vly_400x400.jpg)
![image 2](https://www.rd.com/wp-content/uploads/2018/02/25_Hilarious-Photos-that-Will-Get-You-Through-the-Week_280228817_Doty911.jpg?fit=640,800)

---

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

---

Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

---

### Heading with id {#custom-id}

---

~~strikethrough~~

---

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

---

That is so funny! :joy: :ok_hand:

---

I need to highlight these ==very important words==.

---

H~2~O
  
---

X^2^


