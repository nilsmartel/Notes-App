
# Software Idea: Keynotes

Default Open: ~/.keynotes/global/
-> $item

If $item is dir:
    open sideviewer, showing all entries
    like apple.Notes app.
else:
    hide sideviewer
    show file

```c
fileformat:
    container:
        referenced pdfs, images, csvs, ...
        as files.
    struct File
    - resources:
        list of files, linedrawings, circles etc.
    - placements:
        Array of
            type Placement
            - resourceid // references resource
            - (x, y)
            - (width, height)

```
