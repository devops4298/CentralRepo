{
  "nodeId": 1234,
  "tag": "button",
  "textContent": "Submit",
  "attributes": {
    "id": "submitBtn",
    "class": "btn primary",
    "type": "submit"
  },
  "role": "button",
  "ariaAttributes": {
    "aria-label": "Submit Form"
  },
  "cssClasses": ["btn", "primary"],
  "boundingBox": {
    "x": 120,
    "y": 300,
    "width": 100,
    "height": 40
  },
  "computedStyles": {
    "color": "rgb(255, 255, 255)",
    "background-color": "rgb(0, 123, 255)"
  },
  "xpath": "/html/body/div/form/button[1]",
  "cssSelector": "button.btn.primary",
  "locatorCandidates": [
    { "type": "id", "value": "#submitBtn", "confidence": 1.0 },
    { "type": "getByRole", "value": "button|Submit", "confidence": 0.95 },
    { "type": "getByText", "value": "Submit", "confidence": 0.9 },
    { "type": "css", "value": "button.btn.primary", "confidence": 0.8 },
    { "type": "xpath", "value": "/html/body/div/form/button[1]", "confidence": 0.6 }
  ]
}
