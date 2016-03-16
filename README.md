# SRC attribute value from iframe

Alfred Workflow that extracts src attribute value from iframe tag

## Example:

I have this in my clipboard:

    ```html
    <iframe frameborder="0" style="width:100%;height:207px" src="https://www.draw.io/?chrome=0&db=0&od=0#G0B42SiLJg-CebR0o0UFZ1cWExODQ"></iframe>
    ```

And I want to get this:

    https://www.draw.io/?chrome=0&db=0&od=0#G0B42SiLJg-CebR0o0UFZ1cWExODQ

## How to use

1. Copy some iframe tag into the clipboard
2. Open Alfred
3. Type isrc
5. If all goes well you’ll receive a notification and the src value of the iframe will be on your clipboard ready to be pasted somewhere

## Installation

1. Download the [latest release here](http://github.com/tgirardi/src-from-iframe/releases/latest/)
2. Extract the zip or tar.gz file
3. Inside the extracted folder, double click src-from-iframe.alfredworkflow

## Use Case:

When an app gives you an iframe embed code and you just want the URL
