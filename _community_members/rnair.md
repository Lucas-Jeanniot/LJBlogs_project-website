---
#
# Sample data for community members.
#

# The short name is used to identify related pieces of content in the site. For example it is used in the "authors" array of blog posts, and it is used in the "presenters" array for OpenSearch Conference sessions to identify who is speaking.
# The format for existing values is not normalized. In some cases it is "first-initial-of-first-name" + "last-name", or matching a GitHub username, or something all together random. What is important is that it is unique within the system.
short_name: "rnair"

# The member's full name, or otherwise meaningful preferred name. It is used in the templates for presenting content authors as well as the name of conference speakers.
name: "Rohit Nair"

# The path to the community member's photo.
photo: "/assets/media/community/members/no-image-available.svg"

# Used as the level 1 page header text.
primary_title: 'Rohit Nair'

# Used as the document title displayed in the browser title bar.
title: 'OpenSearch Project Community Member: Rohit Nair'


# Community member job title and company where they work.
job_title_and_company: 'Software Development Engineer'

# Array of conference IDs for which the community member is a keynote speaker, if any, or boolean false otherwise.
# This value is only relevant for member's with the "conference_speaker" user persona.
#keynote_speaker:
#  - '2023-north-america'
# keynote_speaker: false

# The conference topic track for the conference sessions that the user is a speaker. These are shaped as an array of value pairs mapping conference ID and name. 
# For example for the North American conference for the year 2023, and the "Community" track:
session_track: 
  - conference_id: "2024-north-america"
    name: "Operating OpenSearch"

# URL for the community member profile.
permalink: '/community/members/rohit-nair.html'

# Array of community member user personas.
# At this time, only conference_speaker, and author are defined.
personas:
  - conference_speaker


# Array of conference IDs that the member is a speaker.
conference_id:
  - "2024-north-america"


# Optional GitHub username
#github: githubusername

# Optional LinkedIn username
#linkedin: linkedinusername

# Optional Twitter username
#twitter: twitterusername

# Optional Mastodon server url, and username / handle.
#mastodon:
#  url: https://mastodon.social/@mastodonusername
#  name: mastodonusername
---

Markdown or HTML content providing a user bio, or whatever is desired to describe their involvement in open source technology in general, and specifically how their work relates to the OpenSearch Project.
