---
layout: "error_code_page"
title: "Samsung Washer AC6 Error Code"
brand: "Samsung"
device: "Washer"
code: "AC6"
meaningshort: "Communication error between main PCB and inverter PCB."
meaninglong: "The AC6 error indicates that the washer has detected a communication failure between the main control board (PCB) and the inverter PCB, which controls the motor. Samsung notes that depending on the state of the system, the washer may temporarily return to normal operation, but persistent AC6 errors indicate a deeper communication or hardware fault. This error prevents the washer from safely controlling motor speed, torque, and spin cycles."
symptoms:
  - "Washer stops mid‑cycle with AC6 displayed"
  - "Washer attempts to start spinning but stops immediately"
  - "Motor does not respond to control signals"
  - "Washer intermittently resumes normal operation"
  - "Cycle fails to progress past wash or spin phases"
causes:
  - "Loose wiring harness between main PCB and inverter PCB"
  - "Faulty inverter PCB"
  - "Faulty main PCB"
  - "Moisture or corrosion on connectors"
  - "Power fluctuations interrupting communication"
stepfixes:
  - "Turn the washer off and restart the cycle."
  - "Ensure stable household power before running the washer."
  - "Check for moisture around the control panel and base."
  - "If the error persists, the inverter or main PCB may require service."
safetynotes:
  - "Unplug the washer before inspecting internal wiring."
  - "Do not attempt to remove the inverter PCB without proper training."
  - "Avoid operating the washer during electrical storms or brownouts."
modellist:
  - "6000 Series: WW25FG6B34BBAC"

internallinks:
  - "/devices/appliances/washer/samsung/3cp/"
  - "/devices/appliances/washer/samsung/3c/"
  - "/devices/appliances/washer/samsung/uc/"
  - "/devices/appliances/washer/samsung/8c/"
model_specific: "The WW5000F/B700/6000F platforms automatically drain for 3 minutes when water-supply errors appear, and the power button is disabled during this period."
schema_json: |
  {
    "@context": "https://schema.org",
    "@type": "TechArticle",
    "name": "Samsung Washer AC6 Error Code - Inverter Communication Failure",
    "description": "The Samsung washer AC6 error indicates a communication failure between the main PCB and the inverter PCB responsible for motor control.",
    "manufacturer": "Samsung",
    "model": "WW25FG5 / WW5000F / WW6000F"
  }
---