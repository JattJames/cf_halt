# cf_halt

Description:

This is a Very basic Custom Tag for handling the Error, You can use it within cfcatch Block, or It can be used outside the Block anywhere else. This is very basic and its functionality can be enhanced to n levels. You are open to change its functionality to whatever extent you want to and please share the same on riaforge also so other users can also use the Same. This is the Start of this tag and we can build it more better

So looking forward to hear from Developer what this tag needs more and I will give it time to upgrade the Custom tag as much asi can depending upon my work Schedule. 

Other Developers are welcomed to Make changes to this tag

Thanks and Enjoy the Small tag
Last Update:
here is the small usage of this tag

<cftry>
<cfquery datasource="#request.dsn#" name="i">
select * fom mytable
</cfquery>
<cfcatch>
<cf_halt msg="Error! #cfcatch.detail# #cfcatch.message#" 
   animate="yes" 
   animateicon="SomeImagePath or any http image using external site" 
   senduser="Home" target="_self" halt="no" navigateuser="index.cfm"> 
</cfcatch>
</cftry>


ExpandPath can be used to fetch image from the Local folders too
Requirements:
All version of coldfusion From where Custom tags supported Onwards
