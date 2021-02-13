---
title: "9. WebdriverIO vs Selenium Webdriver"
metaTitle: "Difference between WebdriverIO vs Selenium WebDriver"
metaDescription: "Is WebdriverIO or Selenium WebDriver a better automation tool?"
---

# What is Selenium WebDriver?

Selenium WebDriver is one of the oldest automation tools that could use pretty much any programming language.
So you could use, Java, C#, Python etc to use WebDriver. But this not the most user friendly frameworks out there.
So Christian Bromann took it and wrapped it into a good looking candy and called it WebdriverIO.

So WebdriverIO is using Selenium WebDriver under hood, but it's much more user friendly looking one. Chris and other contributors made something like: 
```javascript
await driver.findElement(By.id('fakeId'));.sendKeys('webdriver');
await driver.findElement(By.id('fakeId'));.click();
```
and made it look like this
```javascript
$('#fakeId').setValue('webdriver');
$('#fakeId').click();
```

Much easier, right?

WebDriver/WDIO has a lot of siblings like: Cypress, Protractor, Nightwatch etc. And those are only JS based. 
Selenium WebDriver gave birth to so many different frameworks that can be used in all possible language. So we should definitely say thanks to uncle WebDriver.