# Instruction to Content Writers <!-- omit from toc -->

Below are guidelines for preparing content for the PRC Website. The new design aims to accommodate a substantial amount of content while minimizing the number of templates used. Most pages will have a uniform appearance, with variations primarily in the text from one page to another. To illustrate, I've filled out some content for the estimate program that you can copy and modify.


## Table of Contents <!-- omit from toc -->
<!-- Automatic Table of Content DO NOT EDIT-->
- [General Considerations Applicable to All Pages](#general-considerations-applicable-to-all-pages)
  - [Main Content main.md](#main-content-mainmd)
  - [Section Specific Pages](#section-specific-pages)
  - [Word Counts Restrictions](#word-counts-restrictions)
  - [Inline Media and Links](#inline-media-and-links)
  - [Embedded Content](#embedded-content)
- [Downloadable Datatables](#downloadable-datatables)
- [Specs for News and Events](#specs-for-news-and-events)

<!-- Automatic Table of Content DO NOT EDIT-->
## General Considerations Applicable to All Pages

Content should be provided as plain text with no formatting. Please use the markdown content template to submit your content. a minimum of one piece of content (main.md) is required for each program, but you are welcome to add more as needed:

### Main Content main.md

The `main.md` file contains all the necessary information to populate the design at the [Program Page](../pngs/frame-inner-Txt%20Only.png). This page should include a title, a short description, and full details. See the [Estimate Main Page](./estimate/main.md) for an example. You may also include a methods section here or create a dedicated page for it.

If your program provides downloadable data, you should also complete a data list page using the [data.md template](./data.md).


### Section Specific Pages

- `newsEvent.md` and `team.md`: Use these files to list news and events under the "About Us" section.
- `data.md`: This file is available for some programs and lists all the data available for download for that program.

For listing pages, each item should be separated from the next one by three dashes (`---`).

### Word Counts Restrictions

For consistent display across pages and devices, please adhere to these word count limits.

- Title: Limited to 50 characters. 
- Introduction: Limited to 200 characters.
- Short Description Field - short- : Limited to 150 characters.

### Inline Media and Links

If an image or video needs to appear at a given location within your content, please put the image in the same folder as your content and reference the image as follows:

<exampleImage.png>

Then the remainder of the text continues. Please include an empty line before and after the image.

You can also add an inline link to another page within the website as follows: Please see [Example page](/path/to/page) for more information. For external content, use a URL like [Example page](http://example.com). The same process be used to add link to download data.table.

### Embedded Content

We should streamline all our content to be in plain text as much as possible. If for some reason we MUST insert online embedded content such as iframes, videos, or interactive maps, we will need to discuss on a case-by-case basis.

## Downloadable Datatables

All tables should be provided as downloadable CSV or PDF files. Each program must include its list of downloadable files in a `data.md` file. Refer to [Estimate Data](./estimate/data.md) for more details.

The following specifications apply:

- title: Title of the data table
- year: The year the data file pertains to or the year it was created. If a download pertains to multiple years, include that information in the title.
- short: Optional short description
- path: path/to/file.csv


## Specs for News and Events

All existing events can be added to a single file, separated with a specific formatting. Each event must include a title a date, and a short description. Optionally, you can add full details.

- title: Oregon 2024 Census Data Users Conference
- date: October 24, 2024
- short: The Oregon 2024 Census Data Users Conference will take place remotely over two days on Thursday, October 24 and on November 12th.
- full: https://www.pdx.edu/population-research/state-data-center-events

Full details are optional and can be a link to an external page or unrestricted text.