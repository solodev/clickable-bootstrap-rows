# clickable-bootstrap-rows
You can make basic Bootstrap rows entirely clickable as a link utilizing the JavaScript “onclick” function.

## Tutorial		  
For detailed instruction's, view Solodev's [How to utilize Javascript to make Bootstrap rows clickable](https://www.solodev.com/blog/web-design/how-to-utilize-javascript-to-make-bootstrap-rows-clickable.stml) article.
 
## Demo  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/zydvthb1/4/).

## HTML
The tutorial contains the following basic HTML markup.

```
 <div class="container mt-lg-6 mt-5">
        <div class="row">
          <div class="col-lg-10 col-xl-8 mx-auto text-center pb-5">
            <h1>LunarXP in the news</h1>
            <h3 class="mt-5">
              LunarXP Wins Space Innovator of the Year Award
            </h3>
            <p class="text-pink text-uppercase lead"><strong>October 6, 2019</strong></p>
          </div>
          <div class="bg-hover-white-smoke w-100 pointer" onclick="location.href='#'">
            <div class="container">
              <div class="row py-4 align-items-center border-top clickable-row">
                <div class="col-md-10">
                  <h3 class="h4 m-0">
                    <a href="#">
                      The new bill gives LunarXP a decade-long budget to fulfill the mission of space exploration.
                    </a>
                  </h3>
                </div>
                <div class="col-md-2">
                  <p class="m-0 text-pink text-uppercase">September 24, 2019</p>
                </div>
              </div>
            </div>
          </div>
          <div class="bg-hover-white-smoke w-100 pointer" onclick="location.href='#'">
            <div class="container">
              <div class="row py-4 align-items-center border-top clickable-row">
                <div class="col-md-10">
                  <h3 class="h4 m-0">
                    <a href="#">
                      LunarXP Sets Target for First Mars Landing in 2030
                    </a>
                  </h3>
                </div>
                <div class="col-md-2">
                  <p class="m-0 text-pink text-uppercase">August 14, 2019</p>
                </div>
              </div>
            </div>
          </div>
          <div class="bg-hover-white-smoke w-100 pointer" onclick="location.href='#'">
            <div class="container">
              <div class="row py-4 align-items-center border-top clickable-row">
                <div class="col-md-10">
                  <h3 class="h4 m-0">
                    <a href="#">
                      Habitat Offerings to Include New Hydroponics Lab
                      <i class="fa fa-external-link"></i>
                    </a>
                  </h3>
                </div>
                <div class="col-md-2">
                  <p class="m-0 text-pink text-uppercase">February 11, 2019</p>
                </div>
              </div>
            </div>
          </div>
          <div class="bg-hover-white-smoke w-100 pointer" onclick="location.href='#'">
            <div class="container">
              <div class="row py-4 align-items-center border-top clickable-row">
                <div class="col-md-10">
                  <h3 class="h4 m-0">
                    <a href="#">
                      New Features on the Valkyrie-1 Spacecraft
                    </a>
                  </h3>
                </div>
                <div class="col-md-2">
                  <p class="m-0 text-pink text-uppercase">December 14, 2018</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div> 
```
## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"></script>
```