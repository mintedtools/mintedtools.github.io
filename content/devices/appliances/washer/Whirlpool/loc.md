---
layout: "error_code_page"
title: "Whirlpool Washer LOC Error Code"
brand: "Whirlpool"
device: "Washer"
code: "LOC"
meaningshort: "Control Lock is activated."
meaninglong: "The LOC error indicates that the washer’s Control Lock feature is enabled. When Control Lock is active, all buttons except the power button are disabled to prevent accidental changes during operation. This is not a fault condition but a user‑activated feature. Whirlpool washers display LOC or LC depending on the model and firmware version."
symptoms:
  - "Buttons do not respond"
  - "Washer will not start a cycle"
  - "LOC appears when pressing buttons"
causes:
  - "Control Lock activated intentionally"
  - "Control Lock activated accidentally"
  - "Stuck or unresponsive UI button (rare)"
stepfixes:
  - "Press and hold the Control Lock button for 3 seconds."
  - "Check the user manual for the specific button combination."
  - "Power cycle the washer if the UI is unresponsive."
safetynotes:
  - "Do not force buttons if the UI is locked."
modellist:
  - "WFW75HEFW"
  - "WFW85HEFW"
  - "WFW6620HC"
internallinks:
  - "/devices/appliances/washer/whirlpool/det/"
model_specific: "Some WFW models display LC instead of LOC depending on UI layout."
schema_json: |
  {
    "@context": "https://schema.org",
    "@type": "TechArticle",
    "name": "Whirlpool Washer LOC Error Code - Control Lock Activated",
    "description": "The Whirlpool LOC error indicates that the washer’s Control Lock feature is enabled.",
    "manufacturer": "Whirlpool",
    "model": "WFW Series Front-Load Washers"
  }
---