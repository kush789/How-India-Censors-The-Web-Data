# How India Censors The Web -- Data

A list of URLs potentially blocked by Indian Internet Service Providers.

Please cite the following paper if you use this data it in your work.

Kushagra Singh*, Gurshabad Grover*, and Varun Bansal.  
2020. How India Censors the Web.  
In 12th ACM Conference on Web Science (WebSci ’20), July 6–10, 2020, Southampton, United Kingdom. 
https://doi.org/10.1145/3394231.3397891

## Data Curation and Filtering
We compile the largest-known list of potentially blocked websites from various sources government orders, court orders, user reports, RTI by CIS, list of potentially blocked websites by OONI and miscellaneous.

## Structure for repository is as follows:

- potentially_blocked_urls.txt -> All the urls curated from the various sources
- potentially_blocked_unique_hostnames.txt -> All the unique hostnames derived from the above list
  
## Sources:

- Court Orders
  - [RTI: MeitY provides details of Blocked Websites/URLs](https://sflc.in/rti-meity-provides-details-blocked-websitesurls) -- SFLC.in
  - [COMM_582_2017_.pdf](https://sflc.in/sites/default/files/MeitY_blocked_websites/COMM_582_2017_.pdf) -- SLFC.in
  - [Analysing Latest List of Blocked Sites (Communalism & Rioting Edition)](https://cis-india.org/internet-governance/blog/analysing-blocked-sites-riots-communalism) -- CIS India
  - [Court Order](http://delhihighcourt.nic.in/dhcqrydisp_o.asp?pn=119642&yr=2014) -- Delhi High Court

- Govt Orders
  - [DoT_Letter_3107201_2496720a.PDF](https://web.archive.org/web/20170629024816/https://www.thehindubusinessline.com/multimedia/archive/02496/DoT_Letter_3107201_2496720a.PDF) -- thehindubusinessline.com
  - [List](https://twitter.com/pranesh/status/550196008416600064) by Twitter User @pranesh (Pranesh Prakash)

- Misc
  - [User reports](https://docs.google.com/spreadsheets/d/1O5ToesR8HCcH6bmP_s7s5jN6YlYw4t4l-ovCpmY7xyc/edit#gid=1822363676) collected by Internet Freedom Foundation (as of 15th December, 2020)
  - [DIT's Response to RTI on Website Blocking](https://cis-india.org/internet-governance/blog/rti-response-dit-blocking) -- CIS India
  - [Text of DIT's Response to Second RTI on Website Blocking](https://cis-india.org/internet-governance/dit-response-2nd-rti-blocking) -- CIS India

