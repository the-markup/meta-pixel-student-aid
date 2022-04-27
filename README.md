# Meta Pixel - Student Aid

This repository contains data for our story "[Applied for Student Aid Online? Facebook Saw You]()".

The data comes from participants in [a study](https://rally.mozilla.org/current-studies/facebook-pixel-hunt/) The Markup is conducting on Meta's pixel tracker in collaboration with Mozilla's Rally team.

The dataset provides a list of URLs on the `studentaid.gov` website, where participants' identifiable information was being shared with Facebook. The data was being shared as a part of Meta Pixel's "Advanced Matching" feature, which allows Facebook to connect pixel data from website visitors to Facebook users, even if they do not use Facebook's browser cookies. For more information on what we test for in the pixel event data please refer to the [How We Analyze The Pixel]() Data section of our methodology.

| Column          | Description                                                                                                                                                                                      |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| url             | The URL of the page where the pixel data was captured                                                                                                                                            |
| key             | The Meta Pixel advanced data parameter key. [More information]()                                                                                                                                 |
| key_description | Description of the data parameter in [Meta's documentation](https://web.archive.org/web/20220422143917/https%3A%2F%2Fdevelopers.facebook.com%2Fdocs%2Fmeta-pixel%2Fadvanced%2Fadvanced-matching) |
