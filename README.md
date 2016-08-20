# uk-government-cats

This is not an official list of UK government cats. 

View the [front-end to the data](https://peterkwells.github.io/uk-government-cats/)
View the [dashboard](https://peterkwells.github.io/uk-govt-cat-dashboard)
Created using the [octopub](https://octopub.io/) tool developed by the [ODI Labs team](https://theodi.org/labs)

## Submission guidelines

If you are aware of a cat that works or has worked for the UK government then do submit it to the register for publication by raising a pull request on main list.csv.

In the comments on the pull request please provide some evidence for the data. For example a link to a trusted news source, a picture of the cat on duty, a government press release or even a link to the National Archives.

Data is formatted as follows:

+ uid - a unique ID per cat, starting from 0
+ name - the name of the cat when it was in service
+ status - Active = currently on duty, Deceased = reported dead, In Progress = reported to be starting duty, Inactive = not on duty but not one of the other statuses
+ location - the government department/office where the cat is located
+ startdate - ISO8601 compliant date for start of service
+ enddate - ISO8601 compliant date for end of service
+ wikipage - the cat's Wikipedia page
+ twitterhandle - the cat's Twitter handle

## Dashboard

(Most of) the code for the dashboard is also on [github](https://github.com/peterkwells/uk-govt-cat-dashboard)

## Official registers

Official registers, [authoritative lists that you can trust](https://gds.blog.gov.uk/2015/09/01/registers-authoritative-lists-you-can-trust/), are an important part of a country's [data infrastructure](http://theodi.org/data-infrastructure). To find our more read the [guides](https://www.gov.uk/government/publications/registers/registers) and look at the official [register of registers](http://register.register.gov.uk/).
