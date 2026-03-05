# NS4168 Audio Amplifier Notes

## Overview

Class-D audio amplifier used on CrowPanel and similar ESP32 display boards.

## Specifications

| Feature | Value |
|---------|-------|
Output power | 3W |
Supply voltage | 2.5V – 5.5V |
Efficiency | up to 90% |
Package | SOP-8 |

## Interface

I²S digital audio input from ESP32-S3.

## Notes

The NS4168 is driven via the ESP32 I²S peripheral.
No external filter components required for basic use.
