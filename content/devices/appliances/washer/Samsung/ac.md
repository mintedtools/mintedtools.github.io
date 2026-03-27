---
layout: "error_code_page"
title: "Samsung Washer AC Error Code"
brand: "Samsung"
device: "Washer"
code: "AC"
meaningshort: "Communication error between main and sub control boards."
meaninglong: "The AC error indicates that the washer has detected a communication failure between the main PCB (Primary Control Board) and the sub PCB. Samsung explains that this code appears when the internal control boards cannot exchange signals reliably, often due to wiring issues, loose connectors, or a failing board. Because the washer relies on synchronized communication to manage motor control, water levels, heating, and safety functions, the system halts operation when communication becomes unstable."
symptoms:
  - "Washer stops mid‑cycle with AC displayed"
  - "Washer powers on but will not start a cycle"
  - "Buttons respond slowly or intermittently"
  - "Cycle begins but stops during wash or spin"
  - "Washer restarts unexpectedly"
causes:
  - "Loose wiring harness between control boards"
  - "Moisture intrusion affecting connectors"
  - "Faulty main PCB"
  - "Faulty sub PCB"
  - "Power interruption during board communication"
stepfixes:
  - "Power off the washer and wait 1–2 minutes before restarting."
  - "Ensure the washer is receiving stable household power."
  - "Check for signs of moisture around the control panel."
  - "Restart the cycle after power is restored."
  - "If the error persists, the control boards may require service."
safetynotes:
  - "Unplug the washer before inspecting internal components."
  - "Do not attempt to remove the control boards without proper training."
  - "Avoid operating the washer during electrical storms or power fluctuations."
modellist:
  - "6000 Series: WW25FG6B34BBAC"

  - "5000 Series: WW25FG5B34BEAC"

internallinks:
  - "/devices/appliances/washer/samsung/uc/"
  - "/devices/appliances/washer/samsung/3c/"
  - "/devices/appliances/washer/samsung/1c/"
  - "/devices/appliances/washer/samsung/oc/"
model_specific: "The WW5000F/B700 platform automatically drains for 3 minutes when 4C or related water-supply errors appear, and the power button is disabled during this period."
schema_json: |
  {
    "@context": "https://schema.org",
    "@type": "TechArticle",
    "name": "Samsung Washer AC Error Code - Control Board Communication Failure",
    "description": "The Samsung washer AC error indicates a communication failure between the main and sub control boards, often caused by wiring or PCB issues.",
    "manufacturer": "Samsung",
    "model": "WW25FG5 / WW5000F"
  }
---