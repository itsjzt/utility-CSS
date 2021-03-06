# Common conventions

## Writing code for this project

We follow simple conventions so that code looks consistent.

### Preprocessor
This project uses SCSS as its preprocessor and we try to limit our usage to variables and imports.

### Spaces & Indentation
- Use 2 spaces for indentation.
- Use 1 line gap between different CSS selectors.

### Variables & Mixins
- Use variables instead of spreading pixel and rems around the codebase.
- Introduce a mixin only if that style is used frequently.

### Measurement
- We use rem's throughout the code.
- There are 5 different measures for layout and another 5 for fonts, so don't introduce a new one unless needed.
- Measures are named in `-xs`, `-sm`, `-md`, `-lg`, `-xl` in classes names for more read [Class names](#class-name)

### Class Names
We are making a utility CSS library which interacts with HTML through classes to it is very crucial to create descriptive yet small classes while keeping in mind that they don't clash with class names of popular CSS frameworks.

Keep these things in mind while naming classes
- All layout utility names start with `-{{very short style name}}-{{utility measure (if exists)}}`.

  ex: `-px-sm` stands for padding on X-axis small

- All typography related names start with `-txt-{{short style name}}`.

  ex:  `-txt-sm` stands for text small.

### Pseudo-classes
We don't put lot of focus on pseudo-classes but we have 2 hover classes, they are named in `-{{1 character for pseudo element}}-{{short style name}}`

ex: `-h-opaque`, `-h-shadow`


## Writing docs for this project

### Language
All the docs are written in Markdown.

### Rules
- Use hash or pound (#) for headings.
- Use stars for bolds `**bold**` and underscore for italics `_italics_`.
- provide links to blogs and websites for better clarification.


