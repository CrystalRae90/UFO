# UFO

## Overview of the Analysis

The purpose of this assignment was to refactor the module javascript code to incorporate more filters of the UFO sighting data provided. 

## Results

The module code focused on one filter (date) and was set to filter on clicking a button. This assignment required us to incorportate more filters and driving the filter based on any change events 

The first was the addition of the filter buttons.  As shown below, the webpage now allows for filters for the following parameters: 

![filters.png]("\static\images\filters.png")

This was acheived by adding in a unnumbered list 

             <div class="container-fluid">
                    <div class="row">
                      <div class="col-md-3">
                        <form class="bg-dark">
                          <p>Filter Search</p>
                          <ul class="bg-dark">
                            <ul class="bg-dark">
                              <label for="date">Enter Date</label>
                              <input type="text" placeholder="1/10/2010" id="datetime" />
                            </ul>
                            <ul class="bg-dark">
                                <label for="city">Enter City</label>
                                <input type="text" placeholder="roswell" id="city" />
                            </ul>
                            <ul class="bg-dark">
                                <label for="state">Enter State</label>
                                <input type="text" placeholder="ca" id="state" />
                            </ul>
                            <ul class="bg-dark">
                                <label for="country">Enter Country</label>
                                <input type="text" placeholder="us" id="country" />
                            </ul>
                            <ul class="bg-dark">
                                <label for="shape">Enter State</label>
                                <input type="text" placeholder="circle" id="shape" />
                            </ul>
                          </ul>
                         </form>
                      </div>


## Summary 
