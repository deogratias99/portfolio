---
layout: project
type: project
image: 
title: "HotelBooking"
date: 2024
published: true
labels:
  - Angula
  - Java
  - Html/Css
summary: "Hotel Booking project for school"
---

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can look at the code on [github](https://github.com/deogratias99/Hotel-Booking).
