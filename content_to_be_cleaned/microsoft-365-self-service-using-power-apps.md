---
title: "Microsoft 365 self-service using Power Apps"
date: 2022-01-12T06:00:00-05:00
author: "Jan Bakker"
categories: []
images:
- images/blog/microsoft-365-self-service-using-power-apps/1641653378.png
- images/blog/microsoft-365-self-service-using-power-apps/1641747471.png
- images/blog/microsoft-365-self-service-using-power-apps/1641917465.png
- images/blog/microsoft-365-self-service-using-power-apps/1641748265.png
- images/blog/microsoft-365-self-service-using-power-apps/PowerAppsFlow.png
- images/blog/microsoft-365-self-service-using-power-apps/1641918438.png
- images/blog/microsoft-365-self-service-using-power-apps/JanBakker_0-1641843830957.png
tags: []
type: "regular"
draft: false

---
{{< image alt="1641653378.png" src="images/blog/microsoft-365-self-service-using-power-apps/1641653378.png" >}}


**The idea behind the app**

[[The concept of this app is ]{.NormalTextRun .SCXW211842248
.BCX8}[straightforward]{.NormalTextRun .SCXW211842248 .BCX8}[: it puts
users into groups. And the best part ]{.NormalTextRun .SCXW211842248
.BCX8}[is]{.NormalTextRun .SCXW211842248 .BCX8}]{.TextRun .SCXW211842248
.BCX8 contrast="auto"}[[[:]{.NormalTextRun .SCXW211842248
.BCX8}]{.TextRun .SCXW211842248 .BCX8
contrast="auto"}]{.TrackChangeTextDeletion .TrackedChange .SCXW211842248
.BCX8}[[ they can do it themselves. Now, Microsoft 365 offers a broad
set of ]{.NormalTextRun .SCXW211842248 .BCX8}]{.TextRun .SCXW211842248
.BCX8 contrast="auto"}[[[self-service]{.NormalTextRun .SCXW211842248
.BCX8 ccp-charstyle="Hyperlink"}]{.TextRun .Underlined .SCXW211842248
.BCX8
contrast="none"}](https://janbakker.tech/self-service-in-microsoft-365/){.Hyperlink
.SCXW211842248 .BCX8}[[ capabilities already, but for some
organizations, that can be ]{.NormalTextRun .SCXW211842248 .BCX8}[really
scary]{.NormalTextRun .AdvancedProofingIssueV2 .SCXW211842248 .BCX8}[.
By default, users can even create their own groups and teams themselves,
but this feature is often disabled by ]{.NormalTextRun .SCXW211842248
.BCX8}[IT. ]{.NormalTextRun .AdvancedProofingIssueV2 .SCXW211842248
.BCX8}[ ]{.NormalTextRun .AdvancedProofingIssueV2 .SCXW211842248
.BCX8}[It also might not be the most user-friendly]{.NormalTextRun
.SCXW211842248 .BCX8}[ ]{.NormalTextRun .SCXW211842248
.BCX8}[option]{.NormalTextRun .SCXW211842248 .BCX8}[. ]{.NormalTextRun
.SCXW211842248 .BCX8}]{.TextRun .SCXW211842248 .BCX8
contrast="auto"}[ ]{.EOP .SCXW211842248 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

[[B]{.NormalTextRun .SCXW149660201 .BCX8}[ack to the ]{.NormalTextRun
.SCXW149660201 .BCX8}[concept of ]{.NormalTextRun .SCXW149660201
.BCX8}[groups. These can be either security or Microsoft 365 groups.
Using this app, you can offer self-service to your end-users, while
staying in control. Next to that, you can make it ]{.NormalTextRun
.SCXW149660201 .BCX8}[a ]{.NormalTextRun .SCXW149660201
.BCX8}[user-friendly]{.NormalTextRun .SCXW149660201
.BCX8}[ experience]{.NormalTextRun .SCXW149660201 .BCX8}[, because you
can design your own User Interface around it. So, you can
put ]{.NormalTextRun .SCXW149660201 .BCX8}[additional]{.NormalTextRun
.SCXW149660201 .BCX8}[ information in the UI, as we did in this app.
Since it can be used for every group in Azure AD, this can be used
within all integrated services like Office 365, Microsoft Endpoint
Manager, and even security features like Azure AD Authentication
policies, and Conditional Access.]{.NormalTextRun .SCXW149660201
.BCX8}]{.TextRun .SCXW149660201 .BCX8 contrast="auto"}[ ]{.EOP
.SCXW149660201 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

[[[The ]{.NormalTextRun .SCXW49274579 .BCX8}[ultimate
goal]{.NormalTextRun .AdvancedProofingIssueV2 .SCXW49274579 .BCX8}[ of
this app ]{.NormalTextRun .SCXW49274579 .BCX8}[thus is]{.NormalTextRun
.SCXW49274579 .BCX8}[ a UI where any end-user in the organization
can ]{.NormalTextRun .SCXW49274579 .BCX8}[select what pilot
programs]{.NormalTextRun .SCXW49274579 .BCX8}]{.TextRun .SCXW49274579
.BCX8 contrast="auto"}[[ they want to be part of. In the demo, there are
several different UI elements to help users with their ]{.NormalTextRun
.SCXW49274579 .BCX8}[selection]{.NormalTextRun .SCXW49274579
.BCX8}[ ranging from ]{.NormalTextRun .SCXW49274579
.BCX8}[t]{.NormalTextRun .SCXW49274579 .BCX8}[oggles to ]{.NormalTextRun
.SCXW49274579 .BCX8}[s]{.NormalTextRun .SCXW49274579
.BCX8}[liders. ]{.NormalTextRun .SCXW49274579 .BCX8}]{.TextRun
.SCXW49274579 .BCX8 contrast="auto"}[ ]{.EOP .SCXW49274579 .BCX8
ccp-props="{\"201341983\":0,\"335551550\":1,\"335551620\":1,\"335559739\":160,\"335559740\":259}"}]{.EOP
.SCXW149660201 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

**Features**

[[The idea behind the slider is to bring your users in control of their
modern workplace]{.NormalTextRun .SCXW110568664 .BCX8}[, easier
put:]{.NormalTextRun .SCXW110568664 .BCX8}[ on what
pace ]{.NormalTextRun .SCXW110568664 .BCX8}[updates]{.NormalTextRun
.SCXW110568664 .BCX8}[ will]{.NormalTextRun .SCXW110568664
.BCX8}[ get]{.NormalTextRun .SCXW110568664 .BCX8}[ ]{.NormalTextRun
.SCXW110568664 .BCX8}[delivered]{.NormalTextRun .SCXW110568664
.BCX8}[ ]{.NormalTextRun .SCXW110568664 .BCX8}[to]{.NormalTextRun
.SCXW110568664 .BCX8}[ their Windows device]{.NormalTextRun
.SCXW110568664 .BCX8}[. By choosing a different update channel, they
will be assigned to a specific Windows Update for Business ring in
the back-end]{.NormalTextRun .SCXW110568664 .BCX8}]{.TextRun
.SCXW110568664 .BCX8 contrast="auto"}[[.]{.NormalTextRun .SCXW110568664
.BCX8}]{.TextRun .SCXW110568664 .BCX8 contrast="auto"}[ ]{.EOP
.SCXW110568664 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

{{< image alt="1641747471.png" src="images/blog/microsoft-365-self-service-using-power-apps/1641747471.png" >}}

 

 

[[The toggles]{.NormalTextRun .SCXW127633728 .BCX8}[ can
b]{.NormalTextRun .SCXW127633728 .BCX8}[e used to let the
user ]{.NormalTextRun .SCXW127633728 .BCX8}[participate]{.NormalTextRun
.SCXW127633728 .BCX8}[ in different pilots or features that Microsoft
365 offers. It can also be used to ]{.NormalTextRun .SCXW127633728
.BCX8}[request licenses, for example]{.NormalTextRun .SCXW127633728
.BCX8}[,]{.NormalTextRun .SCXW127633728 .BCX8}[ if the user needs
Power-BI Pro for a specific project. ]{.NormalTextRun .SCXW127633728
.BCX8}[Y]{.NormalTextRun .SCXW127633728 .BCX8}[ou ]{.NormalTextRun
.SCXW127633728 .BCX8}[could ]{.NormalTextRun .SCXW127633728
.BCX8}[even ]{.NormalTextRun .SCXW127633728 .BCX8}[build
an ]{.NormalTextRun .SCXW127633728 .BCX8}[additional]{.NormalTextRun
.SCXW127633728 .BCX8}[ flow ]{.NormalTextRun .SCXW127633728 .BCX8}[that
will ask for manager approval first, or you can make use
of ]{.NormalTextRun .SCXW127633728 .BCX8}]{.TextRun .SCXW127633728 .BCX8
contrast="auto"}[[[Azure Active Directory Access Review]{.NormalTextRun
.SCXW127633728 .BCX8 ccp-charstyle="Hyperlink"}[s]{.NormalTextRun
.SCXW127633728 .BCX8 ccp-charstyle="Hyperlink"}]{.TextRun .Underlined
.SCXW127633728 .BCX8
contrast="none"}](https://janbakker.tech/active-directory-identity-governance-access-reviews/){.Hyperlink
.SCXW127633728 .BCX8}[[ to ]{.NormalTextRun .SCXW127633728 .BCX8}[review
the groups periodically.]{.NormalTextRun .SCXW127633728 .BCX8}]{.TextRun
.SCXW127633728 .BCX8 contrast="auto"}[ ]{.EOP .SCXW127633728 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

[**Group-based licensing** ]{.EOP .SCXW127633728 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

[Leveraging Azure Premium P1, we could use group-based licensing to
automatically assign licenses to users based on group
membership. ]{contrast="auto"}[ ]{ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

[In the Azure portal, go to]{contrast="auto"}**[ Azure Active Directory
-\> Licenses]{contrast="auto"}**[. Select
the preferred licenses, then go to the ]{contrast="auto"}***[Licensed
groups]{contrast="auto"}***[ blade, and click +
Assign. ]{contrast="auto"}[ ]{ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

{{< image alt="1641917465.png" src="images/blog/microsoft-365-self-service-using-power-apps/1641917465.png" >}}

 

 

[[From the list, select the underlying services that you want to assign
to the group.]{.NormalTextRun .SCXW16347456 .BCX8}]{.TextRun
.SCXW16347456 .BCX8 contrast="auto"}[ ]{.EOP .SCXW16347456 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

[{{< image alt="1641748265.png" src="images/blog/microsoft-365-self-service-using-power-apps/1641748265.png" >}}

 

 

[[[As soon as the user is added to the group, the license is
automatically assigned. When the user is removed, ]{.NormalTextRun
.SCXW155582083 .BCX8}[also the license will]{.NormalTextRun
.SCXW155582083 .BCX8}[ be unassigned. ]{.NormalTextRun .SCXW155582083
.BCX8}]{.TextRun .SCXW155582083 .BCX8 contrast="auto"}[ ]{.EOP
.SCXW155582083 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}]{.EOP
.SCXW16347456 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

[[**How does the app work under the hood?**]{.EOP .SCXW155582083 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}]{.EOP
.SCXW16347456 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

[[The app is using Power Automate to connect to the Graph
API. ]{.NormalTextRun .SCXW256519428 .BCX8}[Inside the Power Automate
flow, we use the HTTP connector to send out the API calls. Based on the
parameters that we define in Power ]{.NormalTextRun .SCXW256519428
.BCX8}[Apps,]{.NormalTextRun .ContextualSpellingAndGrammarErrorV2
.SCXW256519428 .BCX8}[ the]{.NormalTextRun .SCXW256519428 .BCX8}[ user
is either added or removed from the group. ]{.NormalTextRun
.SCXW256519428 .BCX8}]{.TextRun .SCXW256519428 .BCX8
contrast="auto"}[ ]{.EOP .SCXW256519428 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

 

[{{< image alt="PowerAppsFlow.png" src="images/blog/microsoft-365-self-service-using-power-apps/PowerAppsFlow.png" >}}

 

 

[[[The flow is using the switch feature to ]{.NormalTextRun
.SCXW23769191 .BCX8}[determine]{.NormalTextRun .SCXW23769191
.BCX8}[ what action should be taken. This can be either
"]{.NormalTextRun .SCXW23769191 .BCX8}[add","remove]{.NormalTextRun
.SpellingErrorV2 .SCXW23769191 .BCX8}[",]{.NormalTextRun
.AdvancedProofingIssueV2 .SCXW23769191 .BCX8}[ or "fetch]{.NormalTextRun
.SCXW23769191 .BCX8}["]{.NormalTextRun .AdvancedProofingIssueV2
.SCXW23769191 .BCX8}[.]{.NormalTextRun .AdvancedProofingIssueV2
.SCXW23769191 .BCX8}[ ]{.NormalTextRun .SCXW23769191 .BCX8}[More details
on the app and flow can be found in the ]{.NormalTextRun .SCXW23769191
.BCX8}]{.TextRun .SCXW23769191 .BCX8 contrast="auto"}[[[[extended
documentation on GitHub]{.NormalTextRun .SCXW23769191 .BCX8
ccp-charstyle="Hyperlink"}]{.TextRun .Underlined .SCXW23769191 .BCX8
contrast="none"}]{.FieldRange .SCXW23769191
.BCX8}](https://github.com/BakkerJan/M365Portal)[[. ]{.NormalTextRun
.SCXW23769191 .BCX8}]{.TextRun .SCXW23769191 .BCX8
contrast="auto"}[ ]{.EOP .SCXW23769191 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}]{.EOP
.SCXW256519428 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

 

[[{{< image alt="1641918438.png" src="images/blog/microsoft-365-self-service-using-power-apps/1641918438.png" >}}

 

**Power Apps in Microsoft Teams**

[[As Power Apps can run ]{.NormalTextRun .SCXW187495681
.BCX8}[natively]{.NormalTextRun .SCXW187495681
.BCX8}[ in ]{.NormalTextRun .SCXW187495681
.BCX8}[Microsoft]{.NormalTextRun .SCXW187495681
.BCX8}[ Teams, ]{.NormalTextRun .SCXW187495681 .BCX8}[t]{.NormalTextRun
.SCXW187495681 .BCX8}[his app can]{.NormalTextRun .SCXW187495681
.BCX8}[ do that]{.NormalTextRun .SCXW187495681 .BCX8}[ ]{.NormalTextRun
.SCXW187495681 .BCX8}[as well]{.NormalTextRun .SCXW187495681 .BCX8}[.
This will make the app ]{.NormalTextRun .SCXW187495681
.BCX8}[easily ]{.NormalTextRun .SCXW187495681 .BCX8}[accessible for
end-users. ]{.NormalTextRun .SCXW187495681 .BCX8}]{.TextRun
.SCXW187495681 .BCX8 contrast="auto"}[ ]{.EOP .SCXW187495681 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

{{< image alt="JanBakker_0-1641843830957.png" src="images/blog/microsoft-365-self-service-using-power-apps/JanBakker_0-1641843830957.png" >}}

 

**How to get started?**

[[This demo app is ]{.NormalTextRun .SCXW177361333 .BCX8}]{.TextRun
.SCXW177361333 .BCX8 contrast="auto"}[[[[available on ]{.NormalTextRun
.SCXW177361333 .BCX8 ccp-charstyle="Hyperlink"}[GitH]{.NormalTextRun
.SCXW177361333 .BCX8 ccp-charstyle="Hyperlink"}[ub]{.NormalTextRun
.SCXW177361333 .BCX8 ccp-charstyle="Hyperlink"}]{.TextRun .Underlined
.SCXW177361333 .BCX8 contrast="none"}]{.FieldRange .SCXW177361333
.BCX8}](https://github.com/BakkerJan/M365Portal)[[ and can
be]{.NormalTextRun .SCXW177361333 .BCX8}[ up and running in
minutes]{.NormalTextRun .SCXW177361333 .BCX8}[. Reach out to this
repository for detailed information and step-by-step
instructions]{.NormalTextRun .SCXW177361333 .BCX8}[.
Also]{.NormalTextRun .SCXW177361333 .BCX8}[,]{.NormalTextRun
.SCXW177361333 .BCX8}[ ]{.NormalTextRun .SCXW177361333 .BCX8}[make sure
to ]{.NormalTextRun .SCXW177361333 .BCX8}[check out ]{.NormalTextRun
.SCXW177361333 .BCX8}]{.TextRun .SCXW177361333 .BCX8
contrast="auto"}[[[[this YouTube video]{.NormalTextRun .SCXW177361333
.BCX8 ccp-charstyle="Hyperlink"}]{.TextRun .Underlined .SCXW177361333
.BCX8 contrast="none"}]{.FieldRange .SCXW177361333
.BCX8}](https://www.youtube.com/watch?v=MzH1Ps6gG7A)[[ for
a ]{.NormalTextRun .SCXW177361333 .BCX8}[short tutorial]{.NormalTextRun
.SCXW177361333 .BCX8}[. ]{.NormalTextRun .AdvancedProofingIssueV2
.SCXW177361333 .BCX8}[ ]{.NormalTextRun .AdvancedProofingIssueV2
.SCXW177361333 .BCX8}[ ]{.NormalTextRun .SCXW177361333 .BCX8}]{.TextRun
.SCXW177361333 .BCX8 contrast="auto"}[ ]{.EOP .SCXW177361333 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

 

[**Conclusion**]{.EOP .SCXW146057552 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}

[[[We hope to have provided some inspiration in ]{.NormalTextRun
.SCXW222105619 .BCX8}[facilitating]{.NormalTextRun .SCXW222105619
.BCX8}[ your ]{.NormalTextRun .SCXW222105619 .BCX8}[end
users]{.NormalTextRun .SCXW222105619 .BCX8}[ with a ]{.NormalTextRun
.SCXW222105619 .BCX8}[self-service]{.NormalTextRun .SCXW222105619
.BCX8}[ e]{.NormalTextRun .SCXW222105619 .BCX8}[xperience using the
Power Platform. Allowing your users to interact with an easy interface
and requesting ]{.NormalTextRun .SCXW222105619 .BCX8}[the features they
feel add]{.NormalTextRun .SCXW222105619 .BCX8}[ value will make sure you
stay in control]{.NormalTextRun .SCXW222105619 .BCX8}[!]{.NormalTextRun
.AdvancedProofingIssueV2 .SCXW222105619 .BCX8}[ ]{.NormalTextRun
.AdvancedProofingIssueV2 .SCXW222105619 .BCX8}[ ]{.NormalTextRun
.AdvancedProofingIssueV2 .SCXW222105619 .BCX8}]{.TextRun .SCXW222105619
.BCX8 contrast="auto"}[ ]{.EOP .SCXW222105619 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}]{.EOP
.SCXW146057552 .BCX8
ccp-props="{\"201341983\":0,\"335559739\":160,\"335559740\":259}"}
:::
:::
:::

::: {#tagsList .TagList .lia-component-tags .lia-component-message-view-widget-tags-list}
-   Tags:
-   [Azure
    AD](/t5/tag/Azure%20AD/tg-p/board-id/Microsoft365PnPBlog){#link_7
    .lia-link-navigation .lia-tag .tag .tag-517 .lia-js-data-tagUid-517}

    ::: {.tag-list-js-confirmation .hidden}
    :::
-   [fusion
    dev](/t5/tag/fusion%20dev/tg-p/board-id/Microsoft365PnPBlog){#link_8
    .lia-link-navigation .lia-tag .tag .tag-1373932
    .lia-js-data-tagUid-1373932}

    ::: {.tag-list-js-confirmation .hidden}
    :::
-   [Groups](/t5/tag/Groups/tg-p/board-id/Microsoft365PnPBlog){#link_9
    .lia-link-navigation .lia-tag .tag .tag-130 .lia-js-data-tagUid-130}

    ::: {.tag-list-js-confirmation .hidden}
    :::
-   [Power
    Apps](/t5/tag/Power%20Apps/tg-p/board-id/Microsoft365PnPBlog){#link_10
    .lia-link-navigation .lia-tag .tag .tag-175 .lia-js-data-tagUid-175}

    ::: {.tag-list-js-confirmation .hidden}
    :::
-   [self-service](/t5/tag/self-service/tg-p/board-id/Microsoft365PnPBlog){#link_11
    .lia-link-navigation .lia-tag .tag .tag-4621
    .lia-js-data-tagUid-4621}

    ::: {.tag-list-js-confirmation .hidden}
    :::
-   [WUfB](/t5/tag/WUfB/tg-p/board-id/Microsoft365PnPBlog){#link_12
    .lia-link-navigation .lia-tag .tag .tag-13579
    .lia-js-data-tagUid-13579}

    ::: {.tag-list-js-confirmation .hidden}
    :::

::: lia-inline-ajax-feedback
::: {#ajaxFeedback .AjaxFeedback}
:::
:::
:::
:::
:::
:::

::: {.lia-quilt-row .lia-quilt-row-footer}
::: {.lia-quilt-column .lia-quilt-column-12 .lia-quilt-column-left .lia-quilt-column-footer-left}
::: {.lia-quilt-column-alley .lia-quilt-column-alley-left}
::: {#kudosButtonV2 .KudosButton .lia-button-image-kudos-wrapper .lia-component-kudos-widget-button-version-3 .lia-component-kudos-widget-button-horizontal .lia-component-kudos-widget-button .lia-component-kudos-action .lia-component-message-view-widget-kudos-action lia-kudos-id="3056109"}
::: {.lia-button-image-kudos .lia-button-image-kudos-horizontal .lia-button-image-kudos-enabled .lia-button-image-kudos-not-kudoed .lia-button-image-kudos-has-kudoes .lia-button-image-kudos-has-kudos .lia-button aria-atomic="true" aria-live="assertive"}
::: lia-button-image-kudos-count
[[ 5 ]{#messageKudosCount_20f034950c863b .MessageKudosCount
.lia-component-kudos-widget-message-kudos-count itemprop="upvoteCount"}[
Likes ]{.lia-button-image-kudos-label
.lia-component-kudos-widget-kudos-count-label}](/t5/kudos/messagepage/board-id/Microsoft365PnPBlog/message-id/656/tab/all-users "Click here to see who gave likes to this post."){#link_13
.lia-link-navigation .kudos-count-link}
:::

::: lia-button-image-kudos-give
[Like](https://techcommunity.microsoft.com/t5/blogs/v2/blogarticlepage.kudosbuttonv2.kudoentity:kudoentity/kudosable-gid/3056109?t:ac=blog-id/Microsoft365PnPBlog/article-id/656&t:cp=kudos/contributions/tapletcontributionspage "Click here to give likes to this post."){#kudoEntity
.lia-link-navigation .kudos-link .lia-link-ticket-post-action}
:::
:::
:::
:::
:::

::: {.lia-quilt-column .lia-quilt-column-12 .lia-quilt-column-right .lia-quilt-column-footer-right}
::: {.lia-quilt-column-alley .lia-quilt-column-alley-right}
::: {.lia-button-group .lia-component-comment-button .lia-component-message-view-widget-comment-button}
:::
:::
:::
:::

::: {.lia-quilt-row .lia-quilt-row-mod-controls}
::: {.lia-quilt-column .lia-quilt-column-24 .lia-quilt-column-single .lia-quilt-column-mod-controls-main}
::: {.lia-quilt-column-alley .lia-quilt-column-alley-single .lia-mark-empty}
:::
:::
:::

::: {.lia-quilt-row .lia-quilt-row-sub-footer}
::: {.lia-quilt-column .lia-quilt-column-24 .lia-quilt-column-single .lia-quilt-column-sub-footer .lia-mark-empty}
:::
:::
:::
:::
:::

::: {#progressBar .lia-progress .lia-js-hidden}
::: lia-progress-indeterminate
:::
:::
:::
:::

[]{#comment-on-this} [ ]{#feedback-successinformationbox_7}

::: {#informationbox_7 .InfoMessage .lia-panel-feedback-banner-note .lia-component-comment-editor}
::: {.lia-text role="alert"}
You must be a registered user to add a comment. If you've already
registered, sign in. Otherwise, register and sign in.

-   [Comment](/plugins/common/feature/oauth2sso/sso_login_redirect?lang=en&redirectreason=permissiondenied&referer=https%3A%2F%2Ftechcommunity.microsoft.com%2Ft5%2Fmicrosoft-365-pnp-blog%2Fmicrosoft-365-self-service-using-power-apps%2Fba-p%2F3056109%23comment-on-this){#link_14
    .lia-link-navigation .blog-link .lia-message-comment-post}
:::
:::
:::
:::

::: {.lia-quilt-column .lia-quilt-column-06 .lia-quilt-column-right .lia-quilt-column-side-content}
::: {.lia-quilt-column-alley .lia-quilt-column-alley-right}
::: {#threadTranslationDashboard .Thread_Translation_Dashboard ng-controller="lingotekThreadTranslationCtrl" li-bindable=""}
::: lingotek-admin-dashboard
:::
:::

::: {style="clear:both"}
:::

::: {#contributorsTaplet .ContributorsTaplet .lia-component-tkb-widget-contributors-taplet}
::: {.lia-panel .lia-panel-standard}
::: lia-decoration-border
::: lia-decoration-border-top
<div>

</div>
:::

::: lia-decoration-border-content
<div>

::: lia-panel-heading-bar-wrapper
::: lia-panel-heading-bar
[ Co-Authors ]{.lia-panel-heading-bar-title aria-level="3"
role="heading"}
:::
:::

::: lia-panel-content-wrapper
::: lia-panel-content
::: {.UserProfileSummary .lia-user-item .lia-js-data-userId-126615 .lia-user-info-group}
::: UserAvatarWrapper
::: {.UserAvatar .lia-user-avatar .lia-component-common-widget-user-avatar .Frequent .Contributor}
[![Jan Bakker](https://techcommunity.microsoft.com/t5/image/serverpage/image-id/318258i55E394610F259AFA/image-dimensions/40x40/image-coordinates/0%2C0%2C1024%2C1024?v=v2 "Jan Bakker"){.lia-user-avatar-message
.user-rank-ring style=""
onerror="replaceBrokenAvatars(this, '/html/assets/default-avatar.png')"}](/t5/user/viewprofilepage/user-id/126615){.UserAvatar
.lia-link-navigation}
:::

::: {.user-profile-card user-id="126615"}
::: contents
::: spinner
:::
:::
:::
:::

::: lia-user-attributes
::: lia-user-name
[ [[Jan
Bakker]{.login-bold}](https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/126615){#link_15
.lia-link-navigation .lia-page-link .lia-user-name-link} ]{.UserName
.lia-user-name .lia-user-rank-Frequent-Contributor}
:::
:::
:::

-   ::: {.UserProfileSummary .lia-user-item .lia-js-data-userId-154 .lia-user-info-group}
    ::: UserAvatarWrapper
    ::: {.UserAvatar .lia-user-avatar .lia-component-common-widget-user-avatar .MVP}
    [![Albert-Jan Schot](https://techcommunity.microsoft.com/t5/image/serverpage/image-id/277287i3F1B4DE667305D80/image-dimensions/40x40/image-coordinates/0%2C0%2C1500%2C1500?v=v2 "Albert-Jan Schot"){.lia-user-avatar-message
    .user-rank-ring .user-rank-ring style="border-color: #107C10"
    onerror="replaceBrokenAvatars(this, '/html/assets/default-avatar.png')"}](/t5/user/viewprofilepage/user-id/154){.UserAvatar
    .lia-link-navigation}
    :::

    ::: {.user-profile-card user-id="154"}
    ::: contents
    ::: spinner
    :::
    :::
    :::
    :::

    ::: lia-user-attributes
    ::: lia-user-name
    [ [Albert-Jan
    Schot](https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/154){#link_16
    .lia-link-navigation .lia-page-link .lia-user-name-link} ]{.UserName
    .lia-user-name .lia-user-rank-MVP}
    :::
    :::
    :::
:::
:::

</div>
:::

::: lia-decoration-border-bottom
<div>

</div>
:::
:::
:::
:::

::: {.lia-panel .lia-panel-standard .ArticleRevisionInfoTaplet .Chrome .lia-component-tkb-widget-article-revision-info-taplet}
::: lia-decoration-border
::: lia-decoration-border-top
<div>

</div>
:::

::: lia-decoration-border-content
<div>

::: lia-panel-heading-bar-wrapper
::: lia-panel-heading-bar
[Version history]{.lia-panel-heading-bar-title aria-level="3"
role="heading"}
:::
:::

::: lia-panel-content-wrapper
::: lia-panel-content
::: lia-revision-info-wrapper
::: lia-revision-info-content
::: {.lia-revision-info-row .lia-revision-last-update-row}
::: lia-revision-info-title-cell
Last update:
:::

::: lia-revision-info-data-cell
[ [‎Jan 12 2022]{.local-date} [07:00 AM]{.local-time} ]{.DateTime}
:::
:::

::: {.lia-revision-info-row .lia-revision-author-row}
::: lia-revision-info-title-cell
Updated by:
:::

::: lia-revision-info-data-cell
[ [[Jan
Bakker]{.login-bold}](https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/126615){#link_17
.lia-link-navigation .lia-page-link .lia-user-name-link} ]{.UserName
.lia-user-name .lia-user-rank-Frequent-Contributor}
:::
:::

::: {.lia-revision-info-row .lia-revision-article-history-link-row .lia-revision-info-data-cell-workflow}
:::
:::
:::
:::
:::

</div>
:::

::: lia-decoration-border-bottom
<div>

</div>
:::
:::
:::

::: {.lia-panel .lia-panel-standard .LabelsTaplet .Chrome .lia-component-labels-widget-labels-list .custom-blog-article-label-widget}
::: lia-decoration-border
::: lia-decoration-border-top
<div>

</div>
:::

::: lia-decoration-border-content
::: lia-panel-heading-bar-wrapper
::: lia-panel-heading-bar
[Labels]{.lia-panel-heading-bar-title aria-level="4" role="heading"}
:::
:::

::: lia-panel-content-wrapper
::: lia-panel-content
::: BlogLabelsTaplet
::: LabelsList
::: {.spinner .labels-spinner}
:::

::: labels-container
:::
:::
:::
:::
:::
:::

::: lia-decoration-border-bottom
<div>

</div>
:::
:::
:::

::: blog-article-social-share-widget-wrapper
::: custom-social-share-component
::: custom-social-share-widget
::: {.lia-panel .lia-panel-standard .Chrome .custom-share-component style=""}
::: lia-decoration-border
::: lia-decoration-border-top
<div>

</div>
:::

::: lia-decoration-border-content
<div>

::: lia-panel-heading-bar-wrapper
::: lia-panel-heading-bar
## Share {#customShareWidget .lia-panel-heading-bar-title .hello}
:::
:::

::: lia-panel-content-wrapper
::: lia-panel-content
-   [[Share to
    LinkedIn]{.social-share-title}](http://www.linkedin.com/shareArticle?mini=true&url=https://techcommunity.microsoft.com/t5/microsoft-365-pnp-blog/microsoft-365-self-service-using-power-apps/ba-p/3056109 "Share to LinkedIn"){.social-share-link
    .social-share-linkedin}
-   [[Share to
    Facebook]{.social-share-title}](http://www.facebook.com/share.php?u=https://techcommunity.microsoft.com/t5/microsoft-365-pnp-blog/microsoft-365-self-service-using-power-apps/ba-p/3056109 "Share to FaceBook"){.social-share-link
    .social-share-facebook}
-   [[Share to
    Twitter]{.social-share-title}](http://twitter.com/share?text=Check%20out%20this%20post%20on%20the%20Microsoft%20Tech%20Community%20:%20Microsoft%20365%20self-service%20using%20Power%20Apps%20-%20Microsoft%20Tech%20Community&url=https://techcommunity.microsoft.com/t5/microsoft-365-pnp-blog/microsoft-365-self-service-using-power-apps/ba-p/3056109 "Share to Twitter"){.social-share-link
    .social-share-twitter}
-   [[Share to
    Email]{.social-share-title}](mailto:?subject=Microsoft%20365%20self-service%20using%20Power%20Apps%20-%20Microsoft%20Tech%20Community&body=I%20found%20this%20on%20the%20Microsoft%20Tech%20Community%20and%20wanted%20to%20share%20it%20with%20you,%20check%20it%20out%20:%20https://techcommunity.microsoft.com/t5/microsoft-365-pnp-blog/microsoft-365-self-service-using-power-apps/ba-p/3056109 "Share via email"){.social-share-link
    .social-share-email}
:::
:::

</div>
:::

::: lia-decoration-border-bottom
<div>

</div>
:::
:::
:::
:::
:::
:::
:::
:::
:::

::: {.lia-quilt-row .lia-quilt-row-footer}
::: {.lia-quilt-column .lia-quilt-column-24 .lia-quilt-column-single .lia-quilt-column-common-footer}
::: {.lia-quilt-column-alley .lia-quilt-column-alley-single}
::: {.lia-quilt .lia-quilt-footer .lia-quilt-layout-footer .lia-component-quilt-footer}
::: {.lia-quilt-row .lia-quilt-row-main}
::: {.lia-quilt-column .lia-quilt-column-24 .lia-quilt-column-single .lia-quilt-column-icons}
::: {.lia-quilt-column-alley .lia-quilt-column-alley-single .lia-mark-empty}
:::
:::
:::
:::
:::
:::
:::
:::
:::
:::
:::
:::

::: {.cse-46444-wa style="display: none"}
::: {.lia-slide-out-nav-menu .lia-component-common-widget-slide-out-nav-menu}
::: {.lia-slide-out-nav-menu-title ng-non-bindable=""}
Browse
:::

::: {.lia-quilt .lia-quilt-navigation-slide-out-menu .lia-quilt-layout-one-column .lia-top-quilt}
::: {.lia-quilt-row .lia-quilt-row-header}
::: {.lia-quilt-column .lia-quilt-column-24 .lia-quilt-column-single .lia-quilt-column-common-header .lia-mark-empty}
:::
:::

::: {.lia-quilt-row .lia-quilt-row-main}
::: {.lia-quilt-column .lia-quilt-column-24 .lia-quilt-column-single .lia-quilt-column-main-content}
::: {.lia-quilt-column-alley .lia-quilt-column-alley-single}
:::
:::
:::

::: {.lia-quilt-row .lia-quilt-row-footer}
::: {.lia-quilt-column .lia-quilt-column-24 .lia-quilt-column-single .lia-quilt-column-common-footer .lia-mark-empty}
:::
:::
:::
:::
:::

::: {.shell-footer bi-view="5xLinks" bi-area="Footer" ms.pgarea="uhffooter" role="contentinfo"}
::: shell-footer-wrapper
::: {.shell-footer-menugroups ms.cmpgrp="footer nav"}
::: {.sfm-group ms.cmpnm="WhatsNew"}
###### What's new  {#whats-new .grp-title}

-   [Surface Pro
    X](https://www.microsoft.com/p/surface-pro-x/8vdnrp2m6hhc?activetab=overview)
-   [Surface Laptop
    3](https://www.microsoft.com/p/surface-laptop-3/8VFGGH1R94TM?activetab=overview)
-   [Surface Pro
    7](https://www.microsoft.com/p/surface-pro-7/8N17J0M5ZZQS?activetab=overview)
-   [Windows 10 Apps](https://www.microsoft.com/windows/windows-10-apps)
-   [Office apps](https://store.office.com/appshome.aspx)
:::

::: {.sfm-group ms.cmpnm="MicrosoftStore"}
###### Microsoft Store  {#microsoft-store .grp-title}

-   [Account profile](https://account.microsoft.com/)
-   [Download Center](https://www.microsoft.com/download)
-   [Microsoft Store
    support](https://go.microsoft.com/fwlink/p/?LinkID=824761&clcid=0x409)
-   [Returns](https://go.microsoft.com/fwlink/p/?LinkID=824764&clcid=0x409)
-   [Order tracking](https://account.microsoft.com/orders)
-   [Store
    locations](https://www.microsoft.com/en-us/store/locations/find-a-store?icid=en-us_UF_FAS)
-   [Buy online, pick up in
    store](https://www.microsoft.com/en-us/store/b/buy-online-pick-up-in-store?icid=uhf_footer_bopuis)
-   [In-store
    events](https://www.microsoft.com/en-us/store/locations/events?icid=en_us_store_uhf_events)
:::

::: {.sfm-group ms.cmpnm="Education"}
###### Education  {#education .grp-title}

-   [Microsoft in education](https://www.microsoft.com/education)
-   [Office for
    students](https://www.microsoft.com/education/products/office/default.aspx)
-   [Office for
    schools](https://products.office.com/academic/compare-office-365-education-plans)
-   [Deals for students and
    parents](https://www.microsoft.com/en-us/store/b/education?icid=CNavfooter_Studentsandeducation)
-   [Microsoft Azure in
    education](https://azure.microsoft.com/community/education/)
:::

::: {.sfm-group ms.cmpnm="Enterprise"}
###### Enterprise  {#enterprise .grp-title}

-   [Azure](https://azure.microsoft.com/)
-   [AppSource](https://go.microsoft.com/fwlink/?LinkID=808093)
-   [Automotive](https://www.microsoft.com/enterprise/automotive)
-   [Government](https://www.microsoft.com/enterprise/government)
-   [Healthcare](https://www.microsoft.com/enterprise/health)
-   [Manufacturing](https://www.microsoft.com/enterprise/manufacturing)
-   [Financial
    Services](https://www.microsoft.com/enterprise/financial-services/banking-and-capital-markets)
-   [Retail](https://www.microsoft.com/enterprise/retail-consumer-goods)
:::

::: {.sfm-group ms.cmpnm="Developer"}
###### Developer  {#developer .grp-title}

-   [Microsoft Visual Studio](https://visualstudio.microsoft.com/)
-   [Window Dev Center](https://developer.microsoft.com/windows)
-   [Developer Network](https://msdn.microsoft.com/)
-   [TechNet](https://technet.microsoft.com/)
-   [Microsoft developer
    program](https://developer.microsoft.com/store/register)
-   [Channel 9](https://channel9.msdn.com/)
-   [Office Dev Center](https://developer.microsoft.com/office)
-   [Microsoft Garage](https://www.microsoft.com/garage/)
:::

::: {.sfm-group ms.cmpnm="Company"}
###### Company  {#company .grp-title}

-   [Careers](https://careers.microsoft.com/)
-   [About Microsoft](https://www.microsoft.com/en-us/about)
-   [Company News](https://news.microsoft.com/)
-   [Privacy at Microsoft](https://privacy.microsoft.com/)
-   [Investors](https://www.microsoft.com/investor/default.aspx)
-   [Diversity and inclusion](https://www.microsoft.com/diversity/)
-   [Accessibility](https://www.microsoft.com/accessibility)
-   [Security](https://www.microsoft.com/security/default.aspx)
:::
:::

::: {.shell-footer-copyright ms.cmpnm="corp" ms.cmpgrp="corp links"}
-   [Sitemap](https://www.microsoft.com/en-us/sitemap1.aspx){#shellmenu_0
    .ctl_footerNavLink}
-   [Contact
    Microsoft](https://support.microsoft.com/contactus){#shellmenu_1
    .ctl_footerNavLink}
-   [Privacy](https://go.microsoft.com/fwlink/?LinkId=521839){#shellmenu_2
    .ctl_footerNavLink}
-   [Manage cookies](#){#shellmenu_2B .ctl_footerNavLink .hidden}
-   [Terms of
    use](http://go.microsoft.com/fwlink/?LinkID=206977){#shellmenu_3
    .ctl_footerNavLink}
-   [Trademarks](https://www.microsoft.com/trademarks){#shellmenu_4
    .ctl_footerNavLink}
-   [Safety and
    eco](https://www.microsoft.com/devices/safety-and-eco){#shellmenu_5
    .ctl_footerNavLink}
-   [About our ads](https://choice.microsoft.com/){#shellmenu_6
    .ctl_footerNavLink}
-   © []{#footerDate} Microsoft
:::
:::
:::
:::