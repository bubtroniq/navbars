# Testing
---
## During Development Testing

Testing was ongoing throughout the entire build. I utilised Firefox developer tools while building to pinpoint and troubleshoot any issues as I went along.
 1. Manually testing each element for appearance and responsiveness via a simulated live server using an extension in VSCode.
 2. Published the page via GitHub pages and used my mobile phone and tablet for testing different screen sizes.
 - Live page link: https://bubtroniq.github.io/mountain_bike_trails/trails.html

 ### Mobile
  |Page|Photo|Result|
  |-------------| -------------|------------|
  |Mobile screenshot of Home page|![alt text](documentation/mobile1.jpg "mobile screenshoots")| As expected |
  | Mobile screenshot of Home page | ![alt text](documentation/mobile2.jpg "mobile screenshoots") | As expected |
  | Mobile screenshot of Home page | ![alt text](documentation/mobile3.jpg "mobile screenshoots") | As expected |
  | Mobile screenshot of Book page | ![alt text](documentation/mobile5.jpg "mobile screenshoots") | As expected |
  | Mobile screenshot of About page | ![alt text](documentation/mobile6.jpg "mobile screenshoots") | As expected |
  | Mobile screenshot of Trails page | ![alt text](documentation/mobile7.jpg "mobile screenshoots") | As expected |
  | Mobile screenshot of Trails page | ![alt text](documentation/mobile8.jpg "mobile screenshoots") | As expected |

### Desktop
  |Page|Photo|Result|
  |-------------| -------------|------------|
  |Desktop screenshot of Home page|![alt text](documentation/desktop1.png "desktop screenshoots")| As expected |
  |Desktop screenshot of Home page|![alt text](documentation/desktop2.png "desktop screenshoots")| As expected |
  |Desktop screenshot of Home page|![alt text](documentation/desktop3.png "desktop screenshoots")| As expected |
  |Desktop screenshot of Trails page|![alt text](documentation/desktop4.png "desktop screenshoots")| As expected |
  |Desktop screenshot of Trails page|![alt text](documentation/desktop5.png "desktop screenshoots")| As expected |
  |Desktop screenshot of Book page|![alt text](documentation/desktop6.png "desktop screenshoots")| As expected |
  |Desktop screenshot of About page|![alt text](documentation/desktop7.png "desktop screenshoots")| As expected |


  
 
 
### Manual Testing
During testing, I used two different browsers to ensure cross-compatibility. The desktop browsers used by myself were:
 1. Firefox
 ![alt text](documentation/firefox1.png "browser screenshoots")
 ![alt text](documentation/firefox2.png "browser screenshoots")
 ![alt text](documentation/firefox3.png "browser screenshoots")
 ![alt text](documentation/firefox4.png "browser screenshoots")
 1. Chrome
 ![alt text](documentation/chrome1.png "browser screenshoots")
 ![alt text](documentation/chrome2.png "browser screenshoots")
 ![alt text](documentation/chrome3.png "browser screenshoots")
 ![alt text](documentation/chrome4.png "browser screenshoots")
 ![alt text](documentation/chrome5.png "browser screenshoots")

I then used the devtools to simulate different screen sizes/devices from 360 px up to 4000px in width.

The following issues were raised during my mid project meeting with my mentor:

* The trails section was overflowing, causing horizontal scrooling on hover
* Footer buttons were wraped in an achor tag, cauzing errors.
* Poor HTML comments
* Semanticaly wrong commit messages.
* To improve forms contrast for better accessibility.

## Post Development Testing

### Validators

[HTML](https://validator.w3.org/nu/)
- index.html
![alt text](documentation/indexhtmlvld.png "html validation")
- trails.html
![alt text](documentation/trailshtmlvld.png "html validation")
- book.html
![alt text](documentation/bookhtmlvld.png "html validation")
- about.html
![alt text](documentation/abouthtmlvld.png "html validation")

[CSS](https://jigsaw.w3.org/css-validator/)
All pages tested via URL and file upload.
 - File upload:
 ![alt text](documentation/cssmanvld.png "css validation")
 - [URL](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fbubtroniq.github.io%2Fmountain_bike_trails)
 - URL CSS validation is showing some errors and warnings from bootstrap.


### Lighthouse Scores 
#### Test Conditions 
 - I did lighthouse test for both mobile and desktop.
 - I asked people to run lighthouse tests from their own devices.
 - I have only included one screenshot as all pages were the same score, only changing by one or two points in performance if I ran it multiple times.

![alt text](documentation/lhdesktop.jpg "lighthouse scores")


### Unfixed Bugs
There are no remaining bugs that I am aware of.




Click to return back to the [README.md](README.md)

