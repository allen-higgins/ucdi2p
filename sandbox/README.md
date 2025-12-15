A working area for experiments.
##  My Markdown test document
This is a sample markdown document to test various features.
### Features to test:
- Headings
- Lists
- Links
- Images
- Code blocks
- Blockquotes
- Tables
- Emphasis (bold, italics)
- Horizontal rules
- Inline code
- Task lists
- Footnotes
- Mermaid diagrams
### Sample Code Block
```python
def hello_world():
    print("Hello, world!")
hello_world()
```
### Sample Table
| Feature       | Description                  |
|---------------|------------------------------|
| Headings      | Different levels of headings |
| Lists         | Ordered and unordered lists  |
| Links         | Hyperlinks to other pages    |
### Sample Link
[OpenAI](https://www.openai.com)
### Sample Image
![OpenAI Logo](https://openai.com/favicon.ico)
### Sample Blockquote
> This is a blockquote example.
### Sample Horizontal Rule
---
### Sample Inline Code
Use the `print()` function to display output in Python.
### Sample Task List
- [x] Write markdown document
- [ ] Test markdown features
### Sample Footnote
This is a sample sentence with a footnote.[^1]
[^1]: This is the footnote text.
### Mermaid diagrams
Enter mermaid code to demonstrate flowchart diagraming
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
Another mermaid diagram
```mermaid
graph TD
    Start((Start)) --> Input[/Input temp/]
    Input --> CheckHigh{temp > 30?}
    
    CheckHigh -- Yes --> PrintHot[/Print "It's hot"/]
    CheckHigh -- No --> CheckLow{temp < 10?}
    
    CheckLow -- Yes --> PrintCold[/Print "It's cold"/]
    CheckLow -- No --> PrintNice[/Print "It's nice"/]
    
    PrintHot --> End((End))
    PrintCold --> End
    PrintNice --> End
```

