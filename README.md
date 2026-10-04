# Robotheca import test

**This is test data, not a real robot. Do not build it.**

This repository exists to test the GitHub import of Robotheca, an
open-source robot library. It holds the smallest set of files the import
reads:

| File | What it tests |
|---|---|
| `robot.yaml` | The robot.yaml standard: when present, the import uses it instead of guessing |
| `urdf/test_arm.urdf` | A two-link arm; one mesh path is relative, the other uses `package://` |
| `stl/base.stl`, `stl/arm.stl` | Two boxes (the "parts"), in millimetres |
| `bom.csv` | A two-line parts list; the names, prices and supplier are placeholders |
| `LICENSE` | MIT, for everything in this repository |

The parts list prices and links (example.com) are made up for testing and do
not describe anything you can buy.
