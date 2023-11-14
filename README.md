# .template
Notes template repository

This is used when a new note repo is created.
It also has the .obsidian configs

The intent here is to store notes structure and related tools info.

---

## Complete structure
`/`
  - home (for meta-data/logistics)
    1. Motivation page
    2. Resources page
    3. Roadmap page
    4. Resource_itineraries directory(Resources with its itinerary)
      - 1. Resource 1 - walkthrough
        - 1. Source Page
        - 2. Chapter 1 (numbered/|named)...
      - 2. Resource 2
      - 3. ...
    5. Projects page
      - 1. Project motivation/context + code + demo links
    6. Setup
  - vault (for mental models)
    - Chapter 1 (named)
    - Chapter 2 (named)
  - assets (contains all images, documents and other (non-markdown) attachments)
  - tooling folder. Try to keep obsidian templates and other stuff here. This isn't strict - tooling files and hidden folders like github.yml can stay outside on the top level.

#### Note/instructions
1. Names should be like so: 1_Name (1. Name), or 1_1_Big for 1.1
2. Assets should be placed inside /assets folder
3. Avoid having both page and folder for the same thing, as much as possible.
4. Use multiple `git` branches (this way, all resources-itineraries and the abstract vault are kept track of): 
  - 1. One for each of the resource-itineraries
  - 2. One for vault
  - 3. Main/master branch which has all resources+vault merged together.

## resource_itineraries folder

fixme: rename (name too long ;))

#### This is for books/videos/courses/seminars/lectures/conferences/problem_sets
#### This a logger of everything that happens
#### It is meant to capture all info, including stuff that has not been incorporated into a/it's mental model.
#### This remains static over time, generally. Only mental models will be updated.

`/`
  - Source link + date + place + motivation for consuming source
  - Chapter 1 (named)
  - Chapter 2 (named)
  - ...

Notes about resource itineraries:
1. Retain resource itinerary chapter number/name as is even when skipping stuff (already in `vault`). This helps in knowing what I've skipped stuff and the fact that I've skipped.
2. Add `in vault` checkbox to all resource itinerary pages. This helps in knowing if the resource page is in vault or not. Pages without an `in vault` are old pages, and are assumed to be `in vault`.
3. If parts of a topic are:
  - 1. Not completely covered in the material
  - 2. I am not able to fully understand it despite effor
4. Problem, or problem sets can also be considered resources, since they directly(or help) populate the vault.

  &emsp; Just add `FIXMEs` with questions for the doubtful parts and move ON. This speeds up understanding and consumption.

## vault
tbd
