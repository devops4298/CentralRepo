{
  "pageUrl": "https://example.com/dashboard",
  "timestamp": "2025-05-28T10:15:30Z",
  "viewport": {
    "width": 1920,
    "height": 1080,
    "deviceScaleFactor": 1
  },
  "elements": [
    {
      "tagName": "button",
      "nodeId": 124,
      "nodeType": 1,
      "shadowRoot": false,
      "customElement": false,
      "frameworkHints": {
        "isMaterialUI": true,
        "isAGGrid": false,
        "isVue": false,
        "isReact": true,
        "isAngular": false
      },
      "attributes": {
        "id": "submitBtn",
        "type": "submit",
        "class": "MuiButton-root MuiButton-contained",
        "aria-label": "Submit",
        "data-testid": "submit-button"
      },
      "cssClasses": [
        "MuiButton-root",
        "MuiButton-contained"
      ],
      "textContent": "Submit",
      "visibleText": "Submit",
      "role": "button",
      "accessibility": {
        "label": "Submit",
        "describedBy": null,
        "labelledBy": null,
        "aria": {
          "aria-label": "Submit",
          "aria-hidden": false,
          "aria-disabled": false,
          "aria-haspopup": false
        }
      },
      "styles": {
        "color": "rgb(255, 255, 255)",
        "backgroundColor": "rgb(33, 150, 243)",
        "fontSize": "14px",
        "fontWeight": "500"
      },
      "boundingBox": {
        "x": 103,
        "y": 450,
        "width": 120,
        "height": 45
      },
      "position": {
        "zIndex": 20,
        "layoutIndex": 142
      },
      "parentHierarchy": [
        {
          "tagName": "form",
          "attributes": { "id": "loginForm", "class": "form-wrapper" },
          "role": "form"
        },
        {
          "tagName": "div",
          "attributes": { "class": "container" },
          "role": null
        }
      ],
      "semanticText": "Submit login form",
      "xpath": "/html/body/div[2]/form/button[1]",
      "cssSelector": "button#submitBtn.MuiButton-root",
      "locatorCandidates": [
        { "type": "id", "value": "#submitBtn", "confidence": 1.0 },
        { "type": "getByRole", "value": "button|Submit", "confidence": 0.95 },
        { "type": "getByText", "value": "Submit", "confidence": 0.9 },
        { "type": "ariaLabel", "value": "[aria-label='Submit']", "confidence": 0.9 },
        { "type": "testId", "value": "[data-testid='submit-button']", "confidence": 0.85 },
        { "type": "css", "value": "button.MuiButton-contained", "confidence": 0.8 },
        { "type": "xpath", "value": "/html/body/div[2]/form/button[1]", "confidence": 0.7 }
      ],
      "events": {
        "onclick": true,
        "onchange": false,
        "oninput": false,
        "onblur": true
      },
      "shadowDom": null,
      "slot": null,
      "frameworkSpecific": {
        "mui": {
          "component": "Button",
          "variant": "contained",
          "color": "primary"
        },
        "agGrid": null
      }
    }
  ]
}
