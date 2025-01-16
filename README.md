# PipesApp

### Technologies
### RouterModule (forRoot + forChild) + Router + routerLink
### @angular/common/locales + registerLocaleData

### Pipes
* lowercase
* uppercase
* titlecase
* date
* number
* currency

### PrimeNg

### STARTUP
####  doc reference:
[primeNG](https://v17.primeng.org/configuration)
#### 1. execute on terminal
```
npm install primeicons@17
npm install primeicons
npm install primeflex
```
#### 2. put on styles.css
```
@import "primeng/resources/themes/lara-dark-indigo/theme.css";
@import "primeng/resources/primeng.css";
@import "primeicons/primeicons.css";
@import "primeflex/primeflex.min.css";
```
### 3. setup ripple
```
public ngOnInit(): void {
  this.primengConfig.ripple = true;
}
```
