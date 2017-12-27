# Automation Testing tips

Sharing &amp; noted some tips when using Automation Frameworks (Selenium, Appium, v.v )

## Getting Started

These are some tips to help you work with Automation Testing Project (Web testing, mobile testing on Android & IOS). Sharing my little experience in some projects that my team worked before.

Note for myself to remember & note my stupid mistakes :)

Updating...

### Reading

Some documents & tips:

[Improving Application Speed and Quality](https://dzone.com/guides/automated-testing-improving-application-speed-and).

[Every programmer should know](https://github.com/mr-mig/every-programmer-should-know)

### Mobile's XPath
[Refer](https://www.w3.org/TR/xpath/#section-Location-Steps)

Not recommend to get Mobile's element by Xpath. Because it's will impact to performance when we run mobile's script. Specially, we can see more clearly when run on IOS's scripts using Appium.

```
example:
//parentnode/Employee[@name='<name>' and @DOB='<dateofbirth>']
//XCUIElementTypeButton[contains(@name,'Edit')]
```
Updating..

### Web Application's XPath

Example 1:
```
 <roofing-material> 

         <manufacturer>Nash</manufacturer> 

         <type>shingles</type> 

      </roofing-material> 
```
```
//roofing-material[type="shingles"][manufacturer="Nash"] 

//roofing-material[type="shingles" and manufacturer="Nash"] 

//roofing-material[type[preceding-sibling::manufacturer="Nash"]="shingles"]
```

Source: [xpath_tips](https://www.xml.com/pub/a/2002/08/14/xpath_tips.html)



## Others tips

Explain how to run the automated tests for this system


## References
* [Readme Template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2#file-readme-template-md/) -  PurpleBooth


## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

* **TonyLai** - *Automation Tips* - [see all examples](https://github.com/anhtuan161)

See also the list of [contributors](https://github.com/anhtuan161) who participated in this project.

## Acknowledgments

* etc

