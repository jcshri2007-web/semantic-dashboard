# Semantic HTML5 & Accessible Component Architecture

A three-page accessible dashboard foundation built with semantic HTML5 and WCAG 2.1 practices. No build step and no dependencies.

## Pages
- `index.html`: dashboard with summary cards and a data table
- `employees.html`: searchable directory table with add and remove modal dialogs
- `settings.html`: account form with fieldsets, validation attributes and status messages

## Structure
```
index.html, employees.html, settings.html
components/
  base.css     colours, focus styles, skip link
  layout.css   header, sidebar, main, footer
  table.css    data tables and toolbar
  form.css     labels, fieldsets, inputs, buttons
  modal.css    dialog styling
  modal.js     dialog open/close and status messages
```

## Semantic tags used
`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `dialog`, `table` with `caption` and `scope`, `fieldset` and `legend`.

## Run
Open `index.html` in a browser. Or run `python -m http.server` in this folder and visit `http://localhost:8000`.

## Validate
Go to https://validator.w3.org/#validate_by_upload and upload each of the three `.html` files.
