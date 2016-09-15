
# Version 0.1.0


## Submission 2 

Hi,

thanks for the comments. I hope I have fixed everything now, see notes below.

Best,
Florian

//

We're seeing the notes you saw, and some others:

> Possibly mis-spelled words in DESCRIPTION:
>   DHARMa (7:18)
>   HierArchical (2:33)

Please put single quotes around software names, and use standard capitalization on English words.

* changed DHARMa to 'DHARMa' (quotation marks)
* changed HierArchical to Hierarchical (although HierArchical was on purpose because of the abbreviation DHARMa)

>
> The Title field should be in title case, current version then in title case:
> 'Residual Diagnostics for HierArchical (Multi-level / Mixed) Regression Models'
> 'Residual Diagnostics for HierArchical (Multi-Level / Mixed) Regression Models'

The issue was changing  "Multi-level" to "Multi-Level"? If that is so, it's changed.

> The Date field is not in ISO 8601 yyyy-mm-dd format.

Please fix.

* changed the date field to 2016-08-25

> ** running examples for arch 'i386' ... [17s] NOTE
> Examples with CPU or elapsed time > 10s
>                    user system elapsed
> simulateResiduals 12.67   0.03   12.72
> ** running examples for arch 'x64' ... [17s] NOTE
> Examples with CPU or elapsed time > 10s
>                    user system elapsed
> simulateResiduals 11.48   0.03   11.45

Please shorten the example code so it runs in 5 sec.

* changed the settings in the help of simulateResiduals() - I hope it is below 5 second now. 

Resubmit when you have made these changes and passed checks without these notes.

Duncan Murdoch 

## Submission 1

### Tested under

* local MAC OS 10.10.5, R 3.3.1
* local Windows 2012 Server, R 3.3.0
* http://win-builder.r-project.org/
 * R-release: R-release, currently R-3.3.1 
 * R-devel: R-devel, to be R-3.4.0

### R CMD check results

#### local

R CMD check results
0 errors | 0 warnings | 0 notes

R CMD check succeeded

#### win-builder

Notes:

Possibly mis-spelled words in DESCRIPTION:
  DHARMa (7:18)
  HierArchical (2:33)
  Multi (2:47)
  autocorrelation (14:5)
  interpretable (8:13)
  misspecification (12:73)
  underdispersion (13:27)

The Title field should be in title case, current version then in title case:
'Residual Diagnostics for HierArchical (Multi-level / Mixed) Regression Models'
'Residual Diagnostics for HierArchical (Multi-Level / Mixed) Regression Models'

--> This seems fine to me. The spelling is as intendend, and the title is in title case