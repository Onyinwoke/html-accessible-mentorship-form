# Assignment 2.8: Form Control Explanation

| Form field or control | HTML input/control type | Why it was selected |
|---|---|---|
| Full name | `text` | Accepts a person's name; uses minimum and maximum lengths. |
| Email address | `email` | Allows the browser to check basic email formatting. |
| Phone number | `tel` | Suits phone numbers and can provide a phone-friendly keyboard on mobile. |
| Date of birth | `date` | Provides a date picker and supports a maximum date. |
| Gender | `radio` | Allows one choice from a related group. |
| Current experience level | `select` and `option` | Provides a consistent list of experience levels. |
| Areas of interest | `checkbox` | Allows applicants to choose multiple interests. |
| Preferred learning track | `select` and `option` | Lets applicants select one track from a defined list. |
| GitHub profile URL | `url` | Checks basic URL formatting in the browser. |
| Motivation | `textarea` | Allows a longer written response, with length constraints. |
| Preferred availability | `select` and `option` | Lets applicants select a preferred schedule. |
| Mentorship rules agreement | `checkbox` | Records an explicit required agreement before submission. |
| Submit Application | `button` with `type="submit"` | Submits the form through the browser's form mechanism. |

## Accessibility and Validation

- Every data-entry control has a visible `<label>` connected to a unique `id` using the matching `for` attribute.
- `<fieldset>` and `<legend>` group related personal, development, and agreement controls.
- Radio buttons share the same `name`, so only one gender option can be selected.
- Checkboxes allow multiple interests, while the agreement checkbox is required.
- `required`, `minlength`, `maxlength`, and `max` provide native browser validation.
- No backend is configured; the form is for HTML practice only.