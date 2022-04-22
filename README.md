::: WordSection1
[Overview]{lang="EN-US"}

[]{lang="EN-US" style="mso-ansi-language:EN-US"}

 

[TODO: Short Introduction, Prerequisites etc.]{lang="EN-US"}

[]{lang="EN-US" style="mso-ansi-language:EN-US"}

 

[Use-Case]{lang="EN-US"}

[]{lang="EN-US" style="mso-ansi-language:EN-US"}

 

[You are a data scientist employed by [ABCOnlineRetailXYZ]{.SpellE} Ltd.
The online retailer has not been doing that great lately and has been
losing customers to competition. While [it is clear that its]{.GramE}
customer churn rates have been growing, figuring out which customers are
more likely to churn is proving hard. ]{lang="EN-US"}[]{lang="EN-US"
style="mso-fareast-font-family:Verdana;mso-bidi-font-family:Verdana"}

[\
]{lang="EN-US" style="mso-fareast-font-family:Verdana;
mso-bidi-font-family:Verdana"}[Your manager came by your desk today,
gave you a couple of files containing some customer-related data and
asked you to build a model helping the business understand which of its
customers may churn [in the near future]{.GramE}, so that Marketing
could proactively target them with personalized incentives and discount
vouchers.]{lang="EN-US"}[]{lang="EN-US"
style="mso-fareast-font-family:Verdana;mso-bidi-font-family:Verdana"}

[You have a lot of other work to do and are a short on
[[time,and]{.GramE}]{.SpellE} are in need of inspiration -- your Python
skills are a bit rusty.]{lang="EN-US"}[\
]{lang="EN-US"
style="mso-fareast-font-family:Verdana;mso-bidi-font-family:Verdana"}[You
are aware that IBM provides market-leading data science tooling and
decide to use
IBM]{lang="EN-US"}[]{dir="RTL"}[[]{dir="RTL"}']{lang="AR-SA" dir="RTL"
style="font-size:12.0pt;mso-ansi-font-size:11.0pt;
line-height:150%;font-family:\"Times New Roman\",serif;mso-ascii-font-family:
\"Helvetica Neue\";mso-ascii-theme-font:major-latin;mso-hansi-font-family:\"Helvetica Neue\";
mso-hansi-theme-font:major-latin"}[s Watson Studio running on
[CPDaaS]{.SpellE} to build and test your
model.]{lang="EN-US"}[]{lang="EN-US" style="mso-fareast-font-family:
Verdana;mso-bidi-font-family:Verdana"}

[]{lang="EN-US" style="font-size:10.0pt;
font-family:\"Verdana\",sans-serif;mso-fareast-font-family:Verdana;mso-bidi-font-family:
Verdana;mso-ansi-language:EN-US"}

 

[![Graphical user interface, application Description automatically
generated](test.fld/image002.jpg){width="402" height="226"
v:shapes="Picture_x0020_1"}]{lang="EN-US"
style="font-size:10.0pt;font-family:
\"Verdana\",sans-serif;mso-fareast-font-family:Verdana;mso-bidi-font-family:Verdana;
mso-style-textoutline-type:none;mso-style-textoutline-outlinestyle-dpiwidth:
0pt;mso-style-textoutline-outlinestyle-linecap:round;mso-style-textoutline-outlinestyle-join:
bevel;mso-style-textoutline-outlinestyle-pctmiterlimit:0%;mso-style-textoutline-outlinestyle-dash:
solid;mso-style-textoutline-outlinestyle-align:center;mso-style-textoutline-outlinestyle-compound:
simple;mso-ansi-language:EN-US;mso-no-proof:yes"}

[Figure
]{lang="EN-US"}[[1]{style="mso-no-proof:yes"}]{lang="EN-US"}[:IBM's
market position]{lang="EN-US"}[]{lang="EN-US" style="font-size:10.0pt;
line-height:150%;font-family:\"Verdana\",sans-serif;mso-fareast-font-family:Verdana;
mso-bidi-font-family:Verdana"}

[]{lang="EN-US"
style="font-size:12.0pt;font-family:\"Verdana\",sans-serif;mso-fareast-font-family:
Verdana;mso-bidi-font-family:Verdana;mso-ansi-language:EN-US"}

 

[IBM]{lang="EN-US"}[]{dir="RTL"}[[]{dir="RTL"}']{lang="AR-SA" dir="RTL"
style="font-size:12.0pt;mso-ansi-font-size:11.0pt;
line-height:150%;font-family:\"Times New Roman\",serif;mso-ascii-font-family:
\"Helvetica Neue\";mso-ascii-theme-font:major-latin;mso-hansi-font-family:\"Helvetica Neue\";
mso-hansi-theme-font:major-latin"}[s Cloud Pak for Data provides a range
of capabilities catering for the whole data science life cycle -- [from
data preparation,]{.GramE} to model build, deployment, training and
monitoring. ]{lang="EN-US"}

[]{lang="EN-US"}

 

[![Graphical user interface, application Description automatically
generated](test.fld/image004.jpg){width="405" height="228"
v:shapes="Picture_x0020_2"}]{lang="EN-US"
style="mso-fareast-font-family:Verdana;mso-bidi-font-family:Verdana;
mso-no-proof:yes"}

[Figure ]{lang="EN-US"}[[2]{style="mso-no-proof:yes"}]{lang="EN-US"}[:
IBM\'s Data Science Portfolio]{lang="EN-US"}[]{lang="EN-US"
style="mso-fareast-font-family:Verdana;mso-bidi-font-family:Verdana"}

[]{lang="EN-US"}

 

[The platform]{lang="EN-US"}[]{dir="RTL"}[[]{dir="RTL"}']{lang="AR-SA"
dir="RTL" style="font-size:12.0pt;mso-ansi-font-size:11.0pt;
line-height:150%;font-family:\"Times New Roman\",serif;mso-ascii-font-family:
\"Helvetica Neue\";mso-ascii-theme-font:major-latin;mso-hansi-font-family:\"Helvetica Neue\";
mso-hansi-theme-font:major-latin"}[s Data Science and ML component(s)
sit under the Watson Studio branding umbrella. Cloud Pak for
Data]{lang="EN-US"}[]{dir="RTL"}[[]{dir="RTL"}']{lang="AR-SA" dir="RTL"
style="font-size:12.0pt;mso-ansi-font-size:11.0pt;
line-height:150%;font-family:\"Times New Roman\",serif;mso-ascii-font-family:
\"Helvetica Neue\";mso-ascii-theme-font:major-latin;mso-hansi-font-family:\"Helvetica Neue\";
mso-hansi-theme-font:major-latin"}[s Watson Studio services (Watson
Studio / Watson Studio Build, Watson Machine Learning / Watson Studio
Deploy, Watson [Openscale]{.SpellE} / Watson Studio Trust) enable the
Build, Run and Manage capabilities of the [MLOps]{.SpellE}
lifecycle.]{lang="EN-US"}

[]{lang="EN-US"}

 

[![Graphical user interface Description automatically generated with
medium confidence](test.fld/image006.jpg){width="402" height="226"
v:shapes="Picture_x0020_3"}]{lang="EN-US"
style="font-family:\"Verdana\",sans-serif;
mso-fareast-font-family:Verdana;mso-bidi-font-family:Verdana;mso-style-textoutline-type:
none;mso-style-textoutline-outlinestyle-dpiwidth:0pt;mso-style-textoutline-outlinestyle-linecap:
round;mso-style-textoutline-outlinestyle-join:bevel;mso-style-textoutline-outlinestyle-pctmiterlimit:
0%;mso-style-textoutline-outlinestyle-dash:solid;mso-style-textoutline-outlinestyle-align:
center;mso-style-textoutline-outlinestyle-compound:simple;mso-ansi-language:
EN-US;mso-no-proof:yes"}

[Figure ]{lang="EN-US"}[[3]{style="mso-no-proof:yes"}]{lang="EN-US"}[:
Watson Studio\'s components]{lang="EN-US"}[]{lang="EN-US"
style="font-family:\"Verdana\",sans-serif;mso-fareast-font-family:Verdana;
mso-bidi-font-family:Verdana"}

[]{lang="EN-US"
style="font-family:\"Verdana\",sans-serif;mso-fareast-font-family:
Verdana;mso-bidi-font-family:Verdana;mso-ansi-language:EN-US"}

 

[]{lang="EN-US"
style="font-size:10.0pt;font-family:\"Verdana\",sans-serif;mso-fareast-font-family:
Verdana;mso-bidi-font-family:Verdana;mso-ansi-language:EN-US"}

 

[In this Lab, you will:]{lang="EN-US"}[]{lang="EN-US"
style="mso-fareast-font-family:Verdana;mso-bidi-font-family:Verdana"}

[]{lang="EN-US" style="mso-fareast-font-family:Verdana;
mso-bidi-font-family:Verdana"}

 

[[·[      
]{style="font:7.0pt \"Times New Roman\""}]{style="mso-list:Ignore"}]{lang="EN-US"
style="font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol"}[[[Use [AutoAI]{.SpellE} to automatically build the most optimal
customer churn prediction model based on your data
sets]{style="text-decoration:none;text-underline:none"}](#bookmark)]{lang="EN-US"}

[[·[      
]{style="font:7.0pt \"Times New Roman\""}]{style="mso-list:Ignore"}]{lang="EN-US"
style="font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol"}[[[And, finally, deploy and test that model with Watson Machine
Learning (Watson Studio Deploy
capabilities).]{style="text-decoration:none;text-underline:none"}](#bookmark1)]{lang="EN-US"}

[]{lang="EN-US" style="mso-fareast-font-family:Verdana;
mso-bidi-font-family:Verdana"}

 

[... [and,]{.GramE} your model will be built (for you!) and deployed in
minutes - not hours or days!]{lang="EN-US"}[]{lang="EN-US"
style="font-size:16.0pt;line-height:150%;font-family:\"Arial Black\",sans-serif;
mso-fareast-font-family:\"Arial Black\";mso-bidi-font-family:\"Arial Black\";
color:blue"}

[]{lang="EN-US" style="mso-ansi-language:
EN-US"}

 
:::
