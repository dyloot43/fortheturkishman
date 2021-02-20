On line 6 replace 'THETURKISHGOD' with any US State with ."findyourunclaimedproperty.com".

Then use sub directories /SWS/application.wadl to view a xml sitemap.

Example:
southdakota.findyourunclaimedproperty.com/SWS/application.wadl

One of the sub dirs (PING)(/SWS/ping) acts like command "GET"
----------------------------------------------------->https://www.colorado.findyourunclaimedproperty.com/SWS/ping<-----------------------------------------------------------------
--------------------------------------------------------------->success<-------------------------------------------------------------------

*  Sub Directory "openapi" (/SWS/openapi) outputs a JSON format and raw data.

*  Sub Directory "/SWS/holders/summaries/{ANYBUSINESS TAX ID FROM THAT STATE}" will out put various information about reported business.
Wells Fargo South Dakota Tax ID:  941347393
---------------------------------------------------->https://southdakota.findyourunclaimedproperty.com/SWS/holders/summaries/941347393---------------------------------------------------->
------------------------------------------------------------->"reportUID":"94134739320171018125751430","taxID":"941347393","holderName":"Wells Fargo Bank N.A.","amount":"0","createDT":"2017-10-18T16:58:01.000+0000"},{"reportUID":"94134739320180105173203357","taxID":"941347393","holderName":"WELLS FARGO HOME MORTGAGE","amount":"0","createDT":"2018-01-05T22:32:11.000+0000"},{"reportUID":"94134739320180125141734800"--------------------------------------------------------->
