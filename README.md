# Material Time Control

NOTE: this is a fork => https://github.com/SteveDunlap13/MaterialTimeControl

A simple time picker component using Angular/Material2 (7+)

## Install

```
npm install
```

## Getting Started

Add to import:
```
import { MaterialTimeControlModule } from 'material-time-control.module';
```

Basic component setup:

You can set a default by setting hours and minutes properties programmatically
```
public exportTime = { hour: 7, minute: 15, meriden: 'PM', format: 12 };
```

Added to template

```
<w-mat-timepicker color="primary" [(userTime)]="exportTime"></w-mat-timepicker>
```


## Dev Getting Started

To run this demo, run

```
npm i
npm start
```

and open http://localhost:4200/ in your browser.

## Build

To build the module run

ng build

### Prerequisites

Required:  
Angular packages: 7+ 
@angular/material: 7+  
@angular/flex-layout: 7+


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Fork from =>  https://github.com/SteveDunlap13/MaterialTimeControl
* Hat tip to <a href="https://github.com/classlinkinc/angular-material-time-picker">classlinkinc/angular-material-time-picker</a>
for the awesome CSS to display the clock component

## Updates

May 5, 2019
- updated all packaged and refactored some dev dep
- added open date picker if input in focused
- cleaned up build errors

Dec 30, 2017
- merged a bunch of improvements from JumpLink (thank you)
- fixed the top of the hour bug noted by JaxonWright
- added 24 hour functionality as requested by Francis-Ide
- updated packages (expect typescript)
