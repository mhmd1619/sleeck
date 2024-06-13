# FlexiCSS

Lightweight css framework that makes the first step for you, by some essentials:

- Grid system.
- Simple elements reset.
- Typography.
- Useful classes (flexbox - spacing - display - text).

## Installation

- Via npm:

```
npm install flexicss
```

then import flexicss.css / flexicss.min.css to the main file of your project.

- Via source:

Just download the flexicss.css / flexicss.min.css from dist folder.

then import flexicss.css / flexicss.min.css to the main file of your project.

## Usage

### Note:

All classes are available for all screens (xl - lg - md -sm).

### Display:

| CSS                   | Class          |
| --------------------- | -------------- |
| display: block        | d-block        |
| display: inline       | d-inline       |
| display: inline-block | d-inline-block |
| display: flex         | d-flex         |
| display: inline-flex  | d-inline-flex  |
| display: grid         | d-grid         |
| display: inline-grid  | d-inline-grid  |
| display: none         | d-none         |

### Flexbox:

| CSS                           | Class                  |
| ----------------------------- | ---------------------- |
| flex-direction: row column... | flex-direction-row     |
| flex-wrap: wrap nowrap...     | flex-wrap-wrap         |
| justify-content: center...    | justify-content-center |
| align-items: center...        | align-items-center     |
| align-content: center...      | align-content-center   |
| align-self: center...         | align-self-center      |
| order: 1 2...                 | order-1                |

### Spacing:

margin and padding values are in `rem` unit.

the range is `0rem,0.1rem,0.2rem....4.8rem,4.9rem,5rem`

| CSS                    | Class   |
| ---------------------- | ------- |
| margin: 0              | m-0     |
| margin: 0 0.1rem       | mx-1    |
| margin: 0.2rem 0       | my-2    |
| margin-top: 4.8rem     | mt-48   |
| margin-bottom: 4.9rem  | mb-49   |
| margin-left: 5rem      | ml-50   |
| margin-right: auto     | mr-auto |
| padding: 0             | p-0     |
| padding: 0 0.1rem      | px-1    |
| padding: 0.2rem 0      | py-2    |
| padding-top: 4.8rem    | pt-48   |
| padding-bottom: 4.9rem | pb-49   |
| padding-left: 5rem     | pl-50   |
| padding-right: auto    | pr-auto |

### Text:

| CSS                               | Class                    |
| --------------------------------- | ------------------------ |
| text-align: center,start...       | text-align-center        |
| text-transform: none,uppercase... | text-transform-uppercase |
| text-wrap: wrap,nowrap            | text-wrap-wrap           |
| word-wrap: normal,break-word      | word-wrap-break-word     |

### Grid System:

Columns are `12`

| xs   | sm      | md      | lg      | xl      |
| ---- | ------- | ------- | ------- | ------- |
| col- | col-sm- | col-md- | col-lg- | col-xl- |

##### Example:

```
<div class="container">
  <div class="row">
    <div class="col-12 col-md-6 col-lg-4">
    1
    </div>
    <div class="col-12 col-md-6 col-lg-4">
    2
    </div>
    <div class="col-12 col-md-6 col-lg-4">
    3
    </div>
  </div>
</div>
```
