# Meta Pixel - Student Aid

This repository contains data for our story "[Applied for Student Aid Online? Facebook Saw You]()".

## Data

The data comes from participants in [a study](https://rally.mozilla.org/current-studies/facebook-pixel-hunt/) The Markup is conducting on Meta's pixel tracker in collaboration with Mozilla's Rally team. To protect the privacy of our panelists, we are only sharing the specific URLs that were sharing personally identifiable with Meta.To protect the privacy of our panelists, we are only sharing the specific URLs that were sharing personally identifiable with Meta.

The data set provides a list of URLs on the `studentaid.gov` website, where participants' identifiable information was being shared with Facebook. The data was being shared as a part of Meta Pixel's "Advanced Matching" feature, which allows Facebook to connect pixel data from website visitors to Facebook users, even if they do not use Facebook's browser cookies. For more information on what we test for in the pixel event data please refer to the [How We Analyze The Pixel]() Data section of our methodology.

| Column          | Description                                                                                                                                                                                      |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| url             | The URL of the page where the pixel data was captured                                                                                                                                            |
| key             | The Meta Pixel advanced data parameter key. [More information]()                                                                                                                                 |
| key_description | Description of the data parameter in [Meta's documentation](https://web.archive.org/web/20220422143917/https%3A%2F%2Fdevelopers.facebook.com%2Fdocs%2Fmeta-pixel%2Fadvanced%2Fadvanced-matching) |

## Screenshot

The screenshot in this repository was taken on March 7th and shows a visit to `studentaid.gov`. We observed the "SubscribedButtonClick" event being sent to https://facebook.com/tr with the request containing the hashed names that were typed in the form on the left. A redacted version of this screenshot also appears in the story.
