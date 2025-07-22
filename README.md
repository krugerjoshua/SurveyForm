# SurveyForm

# 📝 Survey Form Project

## 📋 Objective

Build a survey form that is functionally similar to the [FreeCodeCamp Survey Form Demo](https://survey-form.freecodecamp.rocks).  
**Do not copy** the demo. Put your own spin on it with custom styling and content.

---

## Requirements (User Stories)

Your project must include the following elements:

### Page Structure

- A page title inside an `h1` with `id="title"`.
- A short description inside a `p` with `id="description"`.
- A `form` element with `id="survey-form"`.

### Inputs

Inside the form:

#### Name Input
- `input` field for name
  - `id="name"`
  - `type="text"`
  - `required`
- A corresponding `label` with `id="name-label"`
- Placeholder text included

#### Email Input
- `input` field for email
  - `id="email"`
  - `type="email"`
  - `required`
  - HTML5 validation for proper format
- A corresponding `label` with `id="email-label"`
- Placeholder text included

#### Number Input
- `input` field for number
  - `id="number"`
  - `type="number"`
  - Accepts only numbers
  - Includes `min` and `max` attributes
- A corresponding `label` with `id="number-label"`
- Placeholder text included

#### Dropdown Menu
- A `select` element with `id="dropdown"`
- At least two `<option>` choices

#### Radio Buttons
- Group of at least two `input type="radio"` elements
- All radio buttons grouped with the same `name` attribute

#### Checkboxes
- Group of `input type="checkbox"` elements
- Each checkbox must have a `value` attribute

#### Textarea
- A `textarea` for additional comments

#### Submit Button
- A `button` with `id="submit"` to submit the form

---

## Usage

1. Clone this repository or download the files.
2. Open `index.html` in your browser to view the form.
3. Customize the questions, placeholder text, and styling as desired.
