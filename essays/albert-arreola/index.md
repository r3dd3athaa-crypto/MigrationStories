---
# ============================================================
#  STEP 1 - FILL IN THE INFORMATION BETWEEN THE DASHED LINES
#  Only change the text AFTER the colon on each line.
#  Keep the quotation marks. Lines starting with # are notes.
# ============================================================
layout: essay

# Title of your project
title: "Albert's Project"

# Your name and course (shown under the title)
student: "Your Name"
course: "US Immigration History, Fall 2026"

# Small label on the home page card, e.g. "Village to City"
kicker: "Place to Place"

# One sentence that appears on the home page card and under the title
summary: "One sentence that tells readers what your family's migration story is about."

# Main image: a photograph or object that introduces your family migration story.
# Upload your image into the "images" folder next to this file, then type its file name below.
lead-image: images/placeholder.svg
lead-image-alt: "Short description of the image for screen readers"
lead-image-caption: "What the image shows, who is in it, and the source. Example: Maria and Jose Lopez outside their first apartment, Chicago, 1968. Courtesy of the Lopez family."

# To hide an unfinished essay from the home page, remove the # in front of the next line
# draft: true
---

{% comment %}
  ============================================================
  HOW TO USE THIS TEMPLATE
  ============================================================
  1. Copy this whole "template" folder and rename the copy with your
     name, e.g.  essays/maria-lopez
  2. In YOUR copy, fill in the information at the top of this file.
  3. Replace each paragraph below with your own writing.
     Keep the ## marks, but change the words after them to your own subheader.
  4. To add a picture, audio clip, or video, upload the file into your folder
     (images go in "images", audio goes in "audio") and change the file name
     inside the quotation marks in the matching block below.
  Text in a block like this one is a note. Readers can't see it.
  ============================================================
{% endcomment %}

This is a sample introduction. In a finished essay, this paragraph introduces readers to your family migration story:  naming who they are and their relationship to the student, why they moved, where they moved from and where they settled.It names the people and places and gives just enough background to make readers curious. A student would write about 100 to 120 words here. 

## Subheader 1: The Journey Historical context and impacts (4-8 words)

This section draws upon secondary sources and class materials to explain how the fmaily migration journey relates to the wider history of migration. What broader economic, political, or social developments globally and locally motivated the decision to migrate?  What specific economic, political, and/or social factors encouraged your family to choose a particular destination? Be sure to draw on class readings and other secondary sources here and cite them in Chicago author-date style (author last name, year of publication) with complete citation listed in References section below. 


## Subheader 2: Personal context and impact on family (4-8 words)

{% comment %}
  AUDIO: replace the file name below with your MP3, uploaded to the "audio" folder.
  VIDEO: to use YouTube instead, delete the audio block and paste this in its place:

  {% include essay/video.html
    url="https://www.youtube.com/watch?v=XXXXXXXXXXX"
    caption="10-25 words: who is speaking, what they describe, and a citation."
  %}
{% endcomment %}

{% include essay/audio.html
  file="audio/sample-clip.wav"
  caption="10-25 words: who is speaking, what they describe, and a citation. Interview by Your Name, City, Month Day, Year."
%}

Use a sentence or two to introduce the clip and explain why you chose it.

This sample paragraph describes the journey as a whole. Draw upon your oral history to discuss the personal goals for the family members moving to a different geographic area. Were there personal push (motivations to leave), pull (motivations to move to the destination), or chain migration (family/community connections) factors for migration? What specific opportunities, challenges, disruptions, changes resulted for specific famliy members? How did it meet expectations or require adjustments? Be as specific as you can.  Cite relevant class sources explains how this relates to broader patterns of migration history using  Chicago author-date style (author last name, year of publication) with complete citation listed in References section below. 


## Subheader 3:  Meaningful object, song, food 

 {% include essay/figure.html
  image="/essays/template/images/placeholder.svg"
  alt="Placeholder for a photograph of an important object or place"
  caption="Sample placeholder. Describe what the image shows, why it matters to the story, and where it came from."
%}

 This section describes a particular object, song, recipe, or tradition that is significant for your family migration story. Describe this item using language that evokes touch, smell, sound, sight. Describe any emotions it inspires for your family relating to the migraiton experience -- what was left behind, the journey itself, building a new life, creating new conmmunity? How does this evoke the meaning your family attaches to their migraiton story? If you cite any class materials or seconary sources, be sure to use Chicago author-date style (author last name, year of publication) with complete citation listed in References section below. 

## Subheader 4: 4-8 words Identity and Place in Society

{% include essay/figure.html
  image="/essays/template/images/placeholder.svg"
  alt="Placeholder for an archival photograph"
  caption="Sample placeholder. Describe the archival image, how it relates to other migration stories, and cite its source."
%}

This section explores how your family member identifies, their community, and their sense of belonging. Describe the ways they identify-- as American, as multicultural, as multihyphenate, as an immigrant, etc.  Where do they describe as home, community? What meaning do they apply to where they currently live? Discuss how these ways of identifying and belonging relate to their personal experiences and other migraiton stories we have discussed in class.  Be sure to cite the references to the other stories in this section using Chicago author-date style (author last name, year of publication) with complete citation listed in References section below. 


## Subheader 5: What this project taught me 

This concluding section addresses your experience of doing this project. What did you learn as a result of interviewing a family member? How does this affect your thoughts about your family, migration, and US history and society? A student would write about 70 to 85 words here.

{% comment %}
  OPTIONAL highlighted quotation from the oral history. Paste this where you want it:

  {% include typography/pullquote.html text="\"A short, powerful line from your interview.\"" %}
{% endcomment %}

## References

### Primary sources

Last name, First name. Oral history interview. Interviewed by Your Name. City, Month Day, Year.

### Secondary sources

List the articles, books, and class readings you cited, in Chicago style.
