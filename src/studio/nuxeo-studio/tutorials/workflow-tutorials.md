---
title: Workflow Tutorials
review:
    comment: ''
    date: '2018-01-02'
    status: ok
labels:
    - lts2016-ok
    - lts2017-ok
    - home
    - mlumeau
is_overview: true
confluence:
    ajs-parent-page-id: '19235679'
    ajs-parent-page-title: Educational
    ajs-space-key: NXDOC
    ajs-space-name: Nuxeo Platform Developer Documentation
    canonical: Workflow+Use+Cases
    canonical_source: 'https://doc.nuxeo.com/display/NXDOC/Workflow+Use+Cases'
    page_id: '19235786'
    shortlink: yoMlAQ
    shortlink_source: 'https://doc.nuxeo.com/x/yoMlAQ'
    source_link: /display/NXDOC/Workflow+Use+Cases
tree_item_index: 30
history:
    -
        author: Manon Lumeau
        date: '2016-07-20 12:22'
        message: emove children display macr
        version: '2'
    -
        author: Alain Escaffre
        date: '2014-05-06 01:08'
        message: ''
        version: '1'

---

<div class="row" data-equalizer data-equalize-on="medium">

<div class="column medium-6">
{{#> panel type='secondary' match_height='true'}}
### Simple Workflow Example

Company C has decided to be more rigorous on proposals sent by the sales team. A workflow has to be set up so that each proposal is reviewed by the head of operations, this one being able to decide of an additional juridical control.

[Learn more&nbsp;<i class="fa fa-long-arrow-right" aria-hidden="true"></i>]({{page page='simple-workflow-example'}})
{{/panel}}

{{#> panel type='secondary' match_height='true'}}
### Sub Workflow Example

The subworkflow functionality is the ability to call a workflow from another workflow (creating inception-like workflows), and to pass it variables along the way. The main workflow is suspended while the subworkflow runs, and resumes when the subworkflow ends.

[Learn more&nbsp;<i class="fa fa-long-arrow-right" aria-hidden="true"></i>]({{page page='sub-workflow-example'}})
{{/panel}}
</div>

<div class="column medium-6">
{{#> panel type='secondary' match_height='true'}}
### Workflow Escalation Rules Example

The company OhMyDoc has decided to set up a validation workflow for its press releases, with due dates and automatic escalation to the next step of the workflow after a defined period.

[Learn more&nbsp;<i class="fa fa-long-arrow-right" aria-hidden="true"></i>]({{page page='workflow-escalation-rules-example'}})
{{/panel}}
</div>
</div>

{{#> callout type='info'  heading='Nuxeo University'}}
Watch the related course on Nuxeo University:</br>
[Course on Nuxeo Workflow Configuration](https://university.nuxeo.com/learn/course/external/view/elearning/39/workflow-engine-2021)
{{!--     ### nx_asset ###
    path: /default-domain/workspaces/Product Management/Documentation/Documentation Screenshots/UNIVERSITY/university-wf.png
    name: university-wf.png
    studio_modeler#screenshot#up_to_date
--}}
![university-wf.png](nx_asset://76c9aa68-cc25-4ad5-b007-827c0eb0c188 ?w=450,border=true)
{{/callout}}