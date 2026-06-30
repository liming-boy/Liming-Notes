|       |                                                       |     |
| ----- | ----------------------------------------------------- | --- |
| p-2   | padding: 0.5rem;                                      | 8px |
|       |                                                       |     |
| p-px  | padding: 1px;                                         |     |
|       |                                                       |     |
| px-0  | padding-left: 0;<br><br>padding-right: 0;             |     |
|       |                                                       |     |
| px-1  | padding-left: 0.25rem;<br><br>padding-right: 0.25rem; | 4px |
|       |                                                       |     |
| py-1  | padding-top: 0.25rem;<br><br>padding-bottom: 0.25rem; | 4px |
|       |                                                       |     |
| pt-2  | padding-top: 0.5rem;                                  | 8px |
|       |                                                       |     |
| pr-2  | padding-right: 0.5rem;                                | 8px |
|       |                                                       |     |
| pb-2  | padding-bottom: 0.5rem;                               | 8px |
|       |                                                       |     |
| pl-2  | padding-left: 0.5rem;                                 | 8px |
|       |                                                       |     |
| pt-px | padding-top: 1px;                                     |     |
|       |                                                       |     |
| pr-px | padding-right: 1px;                                   |     |

|      |                                                     |     |
| ---- | --------------------------------------------------- | --- |
| m-1  | margin: 0.25rem;                                    | 4px |
|      |                                                     |     |
| m-px | margin: 1px;                                        |     |
|      |                                                     |     |
| my-1 | margin-top: 0.25rem;<br><br>margin-bottom: 0.25rem; | 4px |
|      |                                                     |     |
| mx-1 | margin-left: 0.25rem;<br><br>margin-right: 0.25rem; | 4px |
|      |                                                     |     |
| -m-1 | margin: -0.25rem;                                   | 4px |
same mr, ml, mb, mt and the negatives

Controls margin between child elements


| space-x-px  | margin-left: 1px;    |      |
| ----------- | -------------------- | ---- |
| -space-x-px | margin-left: -1px;   |      |
| space-y-px  | margin-top: 1px;     |      |
| -space-y-px | margin-top: -1px;    | **** |


| basis-1 | flex-basis: 0.25rem; | 4px |
| ------- | -------------------- | --- |

| gap-1   | gap: 0.25rem;        | 4px |
| ------- | -------------------- | --- |
|         |                      |     |
| gap-x-1 | column-gap: 0.25rem; | 4px |
|         |                      |     |
| gap-y-1 | row-gap: 0.25rem;    | 4px |


| rounded-xs  | border-radius: var(--radius-xs); | 2px  |
| ----------- | -------------------------------- | ---- |
| rounded-sm  | border-radius: var(--radius-sm); | 4px  |
| rounded-md  | border-radius: 0.375rem;         | 6px  |
| rounded-lg  | border-radius: 0.5rem;           | 8px  |
| rounded-xl  | border-radius: 0.75rem;          | 10px |
| rounded-2xl | border-radius: 1rem;             | 12px |
| rounded-3xl | border-radius: 1.5rem;           | 16px |

| rounded-full | border-radius: 9999px;                                                          |     |      |
| ------------ | ------------------------------------------------------------------------------- | --- | ---- |
|              |                                                                                 |     |      |
| rounded-t    | border-top-left-radius: 0.25rem;<br><br>border-top-right-radius: 0.25rem;       | 4px |      |
| rounded-r    | border-top-right-radius: 0.25rem;<br><br>border-bottom-right-radius: 0.25rem;   | 4px |      |
| rounded-b    | border-bottom-right-radius: 0.25rem;<br><br>border-bottom-left-radius: 0.25rem; | 4px |      |
| rounded-l    | border-top-left-radius: 0.25rem;<br><br>border-bottom-left-radius: 0.25rem;     | 4px |      |

|   |   |
|---|---|
|border|border-width: 1px;|
|border-0|border-width: 0;|
|border-2|border-width: 2px;|
|border-4|border-width: 4px;|
|border-8|border-width: 8px;|
|border-t|border-top-width: 1px;|
|border-t-0|border-top-width: 0;|
|border-t-2|border-top-width: 2px;|
Controls the border width between elements.

| divide-x-2 | border-left-width: 2px; |
| ---------- | ----------------------- |
| divide-x-4 | border-left-width: 4px; |
| divide-x-8 | border-left-width: 8px; |
| divide-x   | border-left-width: 1px; |
| divide-y-2 | border-top-width: 2px;  |
| divide-y-4 | border-top-width: 4px;  |
| divide-y-8 | border-top-width: 8px;  |
| divide-y   | border-top-width: 1px;  |
Utilities for controlling the width of an element's outline.

|           |                     |
| --------- | ------------------- |
| outline-0 | outline-width: 0px; |
| outline-1 | outline-width: 1px; |
| outline-2 | outline-width: 2px; |
| outline-4 | outline-width: 4px; |
| outline-8 | outline-width: 8px; |# Outline Style

[Docs](https://tailwindcss.com/docs/outline-style)

Utilities for controlling the style of an element's outline.


|                |                                                      |
| -------------- | ---------------------------------------------------- |
| outline-hidden | outline: 2px solid transparent; outline-offset: 2px; |

# Outline Offset

[Docs](https://tailwindcss.com/docs/outline-offset)

Utilities for controlling the Offset of an element's outline.

|                  |                      |
| ---------------- | -------------------- |
| outline-offset-0 | outline-offset: 0px; |
| outline-offset-1 | outline-offset: 1px; |
| outline-offset-2 | outline-offset: 2px; |
| outline-offset-4 | outline-offset: 4px; |
| outline-offset-8 | outline-offset: 8px; |

# Ring Width

[Docs](https://tailwindcss.com/docs/ring-width)

Utilities for creating outline rings with box-shadows. Note: In v4, the default ring is 1px (use ring-3 for the v3 3px default).

|        |                                                                                                      |                   |
| ------ | ---------------------------------------------------------------------------------------------------- | ----------------- |
| ring-0 | box-shadow: var(--tw-ring-inset) 0 0 0 calc(0px + var(--tw-ring-offset-width)) var(--tw-ring-color); |                   |
| ring-1 | box-shadow: var(--tw-ring-inset) 0 0 0 calc(1px + var(--tw-ring-offset-width)) var(--tw-ring-color); |                   |
| ring-3 | box-shadow: var(--tw-ring-inset) 0 0 0 calc(3px + var(--tw-ring-offset-width)) var(--tw-ring-color); | Same as v3 defaul |

## Typography



# Text Decoration Thickness

[Docs](https://tailwindcss.com/docs/text-decoration-thickness)

Utilities for controlling the thickness of text decorations.

|              |                                 |
| ------------ | ------------------------------- |
| decoration-0 | text-decoration-thickness: 0px; |
| decoration-1 | text-decoration-thickness: 1px; |
| decoration-2 | text-decoration-thickness: 2px; |
| decoration-4 | text-decoration-thickness: 4px; |
| decoration-8 | text-decoration-thickness: 8px; |

# Text Underline Offset

[Docs](https://tailwindcss.com/docs/text-underline-offset)

Utilities for controlling the offset of a text underline.

|                    |                             |
| ------------------ | --------------------------- |
| underline-offset-0 | text-underline-offset: 0px; |
| underline-offset-1 | text-underline-offset: 1px; |
| underline-offset-2 | text-underline-offset: 2px; |
| underline-offset-4 | text-underline-offset: 4px; |
| underline-offset-8 | text-underline-offset: 8px; |

# Text Indent

[Docs](https://tailwindcss.com/docs/text-indent)

Utilities for controlling the amount of empty space shown before text in a block.

|            |                        |      |
| ---------- | ---------------------- | ---- |
| indent-0.5 | text-indent: 0.125rem; | 2px  |
| indent-1   | text-indent: 0.25rem;  | 4px  |
| indent-1.5 | text-indent: 0.375rem; | 6px  |
| indent-2   | text-indent: 0.5rem;   | 8px  |
| indent-2.5 | text-indent: 0.625rem; | 10px |
| indent-3   | text-indent: 0.75rem;  | 12px |
| indent-3.5 | text-indent: 0.875rem; | 14px |
| indent-4   | text-indent: 1rem;     | 16px |

# Vertical Align

[Docs](https://tailwindcss.com/docs/vertical-alignment)

Sets the vertical alignment of an inline or table-cell box.

|                   |                              |
| ----------------- | ---------------------------- |
| align-baseline    | vertical-align: baseline;    |
| align-top         | vertical-align: top;         |
| align-middle      | vertical-align: middle;      |
| align-bottom      | vertical-align: bottom;      |
| align-text-top    | vertical-align: text-top;    |
| align-text-bottom | vertical-align: text-bottom; |
| align-sub         | vertical-align: sub;         |
| align-super       | vertical-align: super;       |

# White Space

[Docs](https://tailwindcss.com/docs/whitespace)

Sets the whitespace of an element.

|                     |                        |
| ------------------- | ---------------------- |
| whitespace-normal   | white-space: normal;   |
| whitespace-nowrap   | white-space: nowrap;   |
| whitespace-pre      | white-space: pre;      |
| whitespace-pre-line | white-space: pre-line; |
| whitespace-pre-wrap | white-space: pre-wrap; |


# Word Break

[Docs](https://tailwindcss.com/docs/word-break)

Sets the word breaks of an element.

|              |                                                   |
| ------------ | ------------------------------------------------- |
| break-normal | overflow-wrap: normal;<br><br>word-break: normal; |
| break-words  | overflow-wrap: break-word;                        |
| break-all    | word-break: break-all;                            |

# Content

[Docs](https://tailwindcss.com/docs/content)

Utilities for controlling the content of the before and after pseudo-elements.

| content-none | content: none; |
| ------------ | -------------- |

# Box Shadow

[Docs](https://tailwindcss.com/docs/box-shadow)

Utilities for controlling the box shadow of an element. Note: In v4, the scale shifted — shadow-sm is now shadow-xs, shadow is now shadow-sm.

|                |                                                    |                     |
| -------------- | -------------------------------------------------- | ------------------- |
| shadow-2xs     | box-shadow: var(--shadow-2xs);                     | New in v4           |
| shadow-xs      | box-shadow: var(--shadow-xs);                      |                     |
| shadow-sm      | box-shadow: var(--shadow-sm);                      |                     |
| shadow         | box-shadow: var(--shadow);                         | Was shadow-md in v3 |
| shadow-md      | box-shadow: var(--shadow-md);                      |                     |
| shadow-lg      | box-shadow: var(--shadow-lg);                      |                     |
| shadow-xl      | box-shadow: var(--shadow-xl);                      |                     |
| shadow-2xl     | box-shadow: var(--shadow-2xl);                     |                     |
| shadow-inner   | box-shadow: inset 0 2px 4px 0 rgba(0, 0, 0, 0.06); |                     |
| shadow-outline | box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.5);     |                     |
| shadow-none    | box-shadow: none;                                  |                     |

# Opacity

[Docs](https://tailwindcss.com/docs/opacity)

|             |                |
| ----------- | -------------- |
| opacity-0   | opacity: 0;    |
| opacity-5   | opacity: 0.05; |
| opacity-10  | opacity: 0.1;  |
| opacity-20  | opacity: 0.2;  |
| opacity-25  | opacity: 0.25; |
| opacity-30  | opacity: 0.3;  |
| opacity-40  | opacity: 0.4;  |
| opacity-50  | opacity: 0.5;  |
| opacity-60  | opacity: 0.6;  |
| opacity-70  | opacity: 0.7;  |
| opacity-75  | opacity: 0.75; |
| opacity-80  | opacity: 0.8;  |
| opacity-90  | opacity: 0.9;  |
| opacity-100 | opacity: 1;    |

New in v4: Utilities for adding inset box shadows to an element.

|                   |                                            |
| ----------------- | ------------------------------------------ |
| inset-shadow-2xs  | box-shadow: inset var(--inset-shadow-2xs); |
| inset-shadow-xs   | box-shadow: inset var(--inset-shadow-xs);  |
| inset-shadow-sm   | box-shadow: inset var(--inset-shadow-sm);  |
| inset-shadow      | box-shadow: inset var(--inset-shadow);     |
| inset-shadow-md   | box-shadow: inset var(--inset-shadow-md);  |
| inset-shadow-lg   | box-shadow: inset var(--inset-shadow-lg);  |
| inset-shadow-none | box-shadow: inset 0 0 #0000;               |

# Tables

# Border Collapse

[Docs](https://tailwindcss.com/docs/border-collapse)

Collapse or separate table borders.

|                 |                            |
| --------------- | -------------------------- |
| border-collapse | border-collapse: collapse; |
| border-separate | border-collapse: separate; |

# Table Layout

[Docs](https://tailwindcss.com/docs/table-layout)

Defines the algorithm used to lay out table cells, rows, and columns.


| table-auto | table-layout: auto; |
| ---------- | ------------------- |

# Interactivity

# Appearance

[Docs](https://tailwindcss.com/docs/appearance)

Disables native styling based on the operating system's theme.


| appearance-none | appearance: none; |
| --------------- | ----------------- |

# Cursor

[Docs](https://tailwindcss.com/docs/cursor)

Changes the cursor when hovering over an element.


| cursor-auto          | cursor: auto;          |
| -------------------- | ---------------------- |
| cursor-default       | cursor: default;       |
| cursor-pointer       | cursor: pointer;       |
| cursor-wait          | cursor: wait;          |
| cursor-text          | cursor: text;          |
| cursor-move          | cursor: move;          |
| cursor-help          | cursor: help;          |
| cursor-not-allowed   | cursor: not-allowed;   |
| cursor-none          | cursor: none;          |
| cursor-context-menu  | cursor: context-menu;  |
| cursor-progress      | cursor: progress;      |
| cursor-cell          | cursor: cell;          |
| cursor-crosshair     | cursor: crosshair;     |
| cursor-vertical-text | cursor: vertical-text; |
| cursor-alias         | cursor: alias;         |
| cursor-copy          | cursor: copy;          |
| cursor-no-drop       | cursor: no-drop;       |
| cursor-grab          | cursor: grab;          |
| cursor-grabbing      | cursor: grabbing;      |
| cursor-all-scroll    | cursor: all-scroll;    |
| cursor-col-resize    | cursor: col-resize;    |
| cursor-row-resize    | cursor: row-resize;    |
| cursor-n-resize      | cursor: n-resize;      |
| cursor-e-resize      | cursor: e-resize;      |
| cursor-s-resize      | cursor: s-resize;      |
| cursor-w-resize      | cursor: w-resize;      |
| cursor-ne-resize     | cursor: ne-resize;     |
| cursor-nw-resize     | cursor: nw-resize;     |
| cursor-se-resize     | cursor: se-resize;     |
| cursor-sw-resize     | cursor: sw-resize;     |
| cursor-ew-resize     | cursor: ew-resize;     |
| cursor-ns-resize     | cursor: ns-resize;     |
| cursor-nesw-resize   | cursor: nesw-resize;   |
| cursor-nwse-resize   | cursor: nwse-resize;   |
| cursor-zoom-in       | cursor: zoom-in;       |
| cursor-zoom-out      | cursor: zoom-out;      |

# Pointer Events

[Docs](https://tailwindcss.com/docs/pointer-events)

Specifies whether an element is the target of mouse events.

|                     |                       |
| ------------------- | --------------------- |
| pointer-events-none | pointer-events: none; |
| pointer-events-auto | pointer-events: auto; |

Sets whether an element is resizable, along with direction.

|             |                     |
| ----------- | ------------------- |
| resize-none | resize: none;       |
| resize      | resize: both;       |
| resize-y    | resize: vertical;   |
| resize-x    | resize: horizontal; |

# Scroll Behavior

[Docs](https://tailwindcss.com/docs/scroll-behavior)

Utilities for controlling the scroll behavior of an element.

|               |                          |
| ------------- | ------------------------ |
| scroll-auto   | scroll-behavior: auto;   |
| scroll-smooth | scroll-behavior: smooth; |

# Scroll Margin

[Docs](https://tailwindcss.com/docs/scroll-margin)

Utilities for controlling the scroll offset around items in a snap container.

|              |                          |     |
| ------------ | ------------------------ | --- |
| scroll-m-0   | scroll-margin: 0;        |     |
| scroll-m-0.5 | scroll-margin: 0.125rem; | 2px |
| scroll-m-1   | scroll-margin: 0.25rem;  | 4px |
| scroll-m-1.5 | scroll-margin: 0.375rem; | 6px |
| scroll-m-2   | scroll-margin: 0.5rem;   | 8px |

|             |                     |
| ----------- | ------------------- |
| scroll-m-px | scroll-margin: 1px; |

|             |                                                                   |     |
| ----------- | ----------------------------------------------------------------- | --- |
| scroll-my-1 | scroll-margin-top: 0.25rem;<br><br>scroll-margin-bottom: 0.25rem; | 4px |
| scroll-mx-1 | scroll-margin-left: 0.25rem;<br><br>scroll-margin-right: 0.25rem; | 4px |

mb, mr, ml,mt 

| scroll-mt-px | scroll-margin-top: 1px;    |
| ------------ | -------------------------- |
| scroll-mr-px | scroll-margin-right: 1px;  |
| scroll-mb-px | scroll-margin-bottom: 1px; |
| scroll-ml-px | scroll-margin-left: 1px;   |

# Scroll Padding

[Docs](https://tailwindcss.com/docs/scroll-padding)

Utilities for controlling an element's scroll offset within a snap container.

|              |                                                                     |     |
| ------------ | ------------------------------------------------------------------- | --- |
| scroll-p-0   | scroll-padding: 0;                                                  |     |
| scroll-p-0.5 | scroll-padding: 0.125rem;                                           | 2px |
| scroll-p-1   | scroll-padding: 0.25rem;                                            | 4px |
|              |                                                                     |     |
| scroll-py-1  | scroll-padding-top: 0.25rem;<br><br>scroll-padding-bottom: 0.25rem; | 4px |
| scroll-px-1  | scroll-padding-left: 0.25rem;<br><br>scroll-padding-right: 0.25rem; | 4px |
scroll-py , px, pb, pl, pt, pr

# Scroll Snap Align

[Docs](https://tailwindcss.com/docs/scroll-snap-align)

Utilities for controlling the scroll snap alignment of an element.

|                 |                                |
| --------------- | ------------------------------ |
| snap-start      | scroll-snap-align: start;      |
| snap-end        | scroll-snap-align: end;        |
| snap-center     | scroll-snap-align: center;     |
| snap-align-none | scroll-snap-align: align-none; |

# Scroll Snap Stop

[Docs](https://tailwindcss.com/docs/scroll-snap-stop)

Utilities for controlling whether you can skip past possible snap positions..

|             |                           |
| ----------- | ------------------------- |
| snap-normal | scroll-snap-stop: normal; |
| snap-always | scroll-snap-stop: always; |

# Scroll Snap Type

[Docs](https://tailwindcss.com/docs/scroll-snap-type)

Utilities for controlling how strictly snap points are enforced in a snap container.

|                |                                                          |
| -------------- | -------------------------------------------------------- |
| snap-none      | scroll-snap-type: none;                                  |
| snap-x         | scroll-snap-type: x var(--tw-scroll-snap-strictness);    |
| snap-y         | scroll-snap-type: y var(--tw-scroll-snap-strictness);    |
| snap-both      | scroll-snap-type: both var(--tw-scroll-snap-strictness); |
| snap-mandatory | --tw-scroll-snap-strictness: mandatory;                  |
| snap-proximity | --tw-scroll-snap-strictness: proximity;                  |

# Touch Action

[Docs](https://tailwindcss.com/docs/touch-action)

Utilities for controlling how an element can be scrolled and zoomed on touchscreens.

|                    |                             |
| ------------------ | --------------------------- |
| touch-auto         | touch-action: auto;         |
| touch-none         | touch-action: none;         |
| touch-pan-x        | touch-action: pan-x;        |
| touch-pan-left     | touch-action: pan-left;     |
| touch-pan-right    | touch-action: pan-right;    |
| touch-pan-y        | touch-action: pan-y;        |
| touch-pan-up       | touch-action: pan-up;       |
| touch-pan-down     | touch-action: pan-down;     |
| touch-pinch-zoom   | touch-action: pinch-zoom;   |
| touch-manipulation | touch-action: manipulation; |

# User Select

[Docs](https://tailwindcss.com/docs/user-select)

Controls whether the user can select text.

|             |                    |
| ----------- | ------------------ |
| select-none | user-select: none; |
| select-text | user-select: text; |
| select-all  | user-select: all;  |
| select-auto | user-select: auto; |

# Will Change

[Docs](https://tailwindcss.com/docs/will-change)

Utilities for optimizing upcoming animations of elements that are expected to change.

|                       |                               |
| --------------------- | ----------------------------- |
| will-change-auto      | will-change: auto;            |
| will-change-scroll    | will-change: scroll-position; |
| will-change-contents  | will-change: contents;        |
| will-change-transform | will-change: transform;       |

# ield Sizing

[Docs](https://tailwindcss.com/docs/field-sizing)

New in v4: Utilities to auto-resize form fields based on their content (no JavaScript needed).

|                      |                        |                          |
| -------------------- | ---------------------- | ------------------------ |
| field-sizing-fixed   | field-sizing: fixed;   | Default behavior         |
| field-sizing-content | field-sizing: content; | Auto-resize with content |

# Tables

# Border Collapse

[Docs](https://tailwindcss.com/docs/border-collapse)

Collapse or separate table borders.

|                 |                            |
| --------------- | -------------------------- |
| border-collapse | border-collapse: collapse; |
| border-separate | border-collapse: separate; |

# Table Layout

[Docs](https://tailwindcss.com/docs/table-layout)

Defines the algorithm used to lay out table cells, rows, and columns.

|             |                      |
| ----------- | -------------------- |
| table-auto  | table-layout: auto;  |
| table-fixed | table-layout: fixed; |



# Layout

# Aspect Ratio

[Docs](https://tailwindcss.com/docs/aspect-ratio)

Utilities for controlling the aspect ratio of an element.

|               |                       |
| ------------- | --------------------- |
| aspect-auto   | aspect-ratio: auto;   |
| aspect-square | aspect-ratio: 1 / 1;  |
| aspect-video  | aspect-ratio: 16 / 9; |

# Container

[Docs](https://tailwindcss.com/docs/container)

Sets the max-width to match the min-width of the current breakpoint.

|           |              |                    |
| --------- | ------------ | ------------------ |
| container | none         | width: 100%        |
|           | sm (640px)   | max-width: 640px;  |
|           | md (768px)   | max-width: 768px;  |
|           | lg (1024px)  | max-width: 1024px; |
|           | xl (1280px)  | max-width: 1280px; |
|           | 2xl (1536px) | max-width: 1536px; |

# Columns

[Docs](https://tailwindcss.com/docs/columns)

Utilities for controlling the number of columns within an element.

|           |             |
| --------- | ----------- |
| columns-1 | columns: 1; |
| columns-2 | columns: 2; |
| columns-3 | columns: 3; |


|              |                 |
| ------------ | --------------- |
| columns-auto | columns: auto;  |
| columns-3xs  | columns: 16rem; |
| columns-2xs  | columns: 18rem; |
| columns-xs   | columns: 20rem; |
| columns-sm   | columns: 24rem; |
| columns-md   | columns: 28rem; |
| columns-lg   | columns: 32rem; |
| columns-xl   | columns: 36rem; |
| columns-2xl  | columns: 42rem; |
| columns-3xl  | columns: 48rem; |
| columns-4xl  | columns: 56rem; |
| columns-5xl  | columns: 64rem; |
| columns-6xl  | columns: 72rem; |
| columns-7xl  | columns: 80rem; |
# Break After

[Docs](https://tailwindcss.com/docs/break-after)

Utilities for controlling how a column or page should break after an element.

|                        |                          |
| ---------------------- | ------------------------ |
| break-after-auto       | break-after: auto;       |
| break-after-avoid      | break-after: avoid;      |
| break-after-all        | break-after: all;        |
| break-after-avoid-page | break-after: avoid-page; |
| break-after-page       | break-after: page;       |
| break-after-left       | break-after: left;       |
| break-after-right      | break-after: right;      |
| break-after-column     | break-after: column;     |

# Break Before

[Docs](https://tailwindcss.com/docs/break-before)

Utilities for controlling how a column or page should break before an element.

|                         |                           |
| ----------------------- | ------------------------- |
| break-before-auto       | break-before: auto;       |
| break-before-avoid      | break-before: avoid;      |
| break-before-all        | break-before: all;        |
| break-before-avoid-page | break-before: avoid-page; |
| break-before-page       | break-before: page;       |
| break-before-left       | break-before: left;       |
| break-before-right      | break-before: right;      |
| break-before-column     | break-before: column;     |

# Break Inside

[Docs](https://tailwindcss.com/docs/break-inside)

Utilities for controlling how a column or page should break within an element.

|                         |                           |
| ----------------------- | ------------------------- |
| break-inside-auto       | break-inside: auto;       |
| break-inside-avoid      | break-inside: avoid;      |
| break-inside-avoid-page | break-inside: avoid-page; |
| break-inside-column     | break-inside: column;     |

# Box Sizing

[Docs](https://tailwindcss.com/docs/box-sizing)

Sets how the total width and height of an element is calculated.

|             |                          |
| ----------- | ------------------------ |
| box-border  | box-sizing: border-box;  |
| box-content | box-sizing: content-box; |

# Display

[Docs](https://tailwindcss.com/docs/display)

Sets the display box type of an element.

|                    |                              |
| ------------------ | ---------------------------- |
| block              | display: block;              |
| inline-block       | display: inline-block;       |
| inline             | display: inline;             |
| flex               | display: flex;               |
| inline-flex        | display: inline-flex;        |
| table              | display: table;              |
| inline-table       | display: inline-table;       |
| table-caption      | display: table-caption;      |
| table-cell         | display: table-cell;         |
| table-column       | display: table-column;       |
| table-column-group | display: table-column-group; |
| table-footer-group | display: table-footer-group; |
| table-header-group | display: table-header-group; |
| table-row-group    | display: table-row-group;    |
| table-row          | display: table-row;          |
| flow-root          | display: flow-root           |
| grid               | display: grid                |
| inline-grid        | display: inline-grid         |
| contents           | display: contents;           |
| list-item          | display: list-item;          |
| hidden             | display: none;               |

# Float

[Docs](https://tailwindcss.com/docs/floats)

Sets an element's placement to a side of its container and allows content to wrap around it.

|             |               |
| ----------- | ------------- |
| float-right | float: right; |
| float-left  | float: left;  |
| float-none  | float: none;  |

# Clear

[Docs](https://tailwindcss.com/docs/clear)

Sets whether an element is moved below preceding floated elements.

|             |               |
| ----------- | ------------- |
| clear-left  | clear: left;  |
| clear-right | clear: right; |
| clear-both  | clear: both;  |
| clear-none  | clear: none;  |

# Isolation

[Docs](https://tailwindcss.com/docs/isolation)

Sets whether an element is moved below preceding floated elements.

|              |                     |
| ------------ | ------------------- |
| isolate      | isolation: isolate; |
| isolate-auto | isolation: auto;    |

# Object Fit

[Docs](https://tailwindcss.com/docs/object-fit)

Sets how the content of a replaced element (img or video tag) should be resized.


| object-contain    | object-fit: contain;    |
| ----------------- | ----------------------- |
| object-cover      | object-fit: cover;      |
| object-fill       | object-fit: fill;       |
| object-none       | object-fit: none;       |
| object-scale-down | object-fit: scale-down; |

# Object Position

[Docs](https://tailwindcss.com/docs/object-position)

Sets the alignment of the selected replaced element.

|                     |                                |
| ------------------- | ------------------------------ |
| object-bottom       | object-position: bottom;       |
| object-center       | object-position: center;       |
| object-left         | object-position: left;         |
| object-left-bottom  | object-position: left bottom;  |
| object-left-top     | object-position: left top;     |
| object-right        | object-position: right;        |
| object-right-bottom | object-position: right bottom; |
| object-right-top    | object-position: right top;    |
| object-top          | object-position: top;          |

# Overflow

[Docs](https://tailwindcss.com/docs/overflow)

Sets how to handle content that's too big for its container.

|                    |                                    |
| ------------------ | ---------------------------------- |
| overflow-auto      | overflow: auto;                    |
| overflow-x-auto    | overflow-x: auto;                  |
| overflow-y-auto    | overflow-y: auto;                  |
| overflow-hidden    | overflow: hidden;                  |
| overflow-x-hidden  | overflow-x: hidden;                |
| overflow-y-hidden  | overflow-y: hidden;                |
| overflow-visible   | overflow: visible;                 |
| overflow-x-visible | overflow-x: visible;               |
| overflow-y-visible | overflow-y: visible;               |
| overflow-scroll    | overflow: scroll;                  |
| overflow-x-scroll  | overflow-x: scroll;                |
| overflow-y-scroll  | overflow-y: scroll;                |
| scrolling-touch    | -webkit-overflow-scrolling: touch; |
| scrolling-auto     | -webkit-overflow-scrolling: auto;  |

# Overscroll Behavior

[Docs](https://tailwindcss.com/docs/overscroll-behavior)

Sets of utilities for controlling how the browser behaves when reaching the boundary of a scrolling area.

|                      |                                 |
| -------------------- | ------------------------------- |
| overscroll-auto      | overscroll-behavior: auto;      |
| overscroll-y-auto    | overscroll-behavior-y: auto;    |
| overscroll-x-auto    | overscroll-behavior-x: auto;    |
| overscroll-contain   | overscroll-behavior: contain;   |
| overscroll-y-contain | overscroll-behavior-y: contain; |
| overscroll-x-contain | overscroll-behavior-x: contain; |
| overscroll-none      | overscroll-behavior: none;      |
| overscroll-y-none    | overscroll-behavior-y: none;    |
| overscroll-x-none    | overscroll-behavior-x: none;    |

# Position

[Docs](https://tailwindcss.com/docs/positioning)

Sets an element's position.

| static   | position: static;   |
| -------- | ------------------- |
| fixed    | position: fixed;    |
| absolute | position: absolute; |
| relative | position: relative; |
| sticky   | position: sticky;   |

# Top / Right / Bottom / Left

[Docs](https://tailwindcss.com/docs/top-right-bottom-left)

Sets the placement of a positioned element.


| inset-0      | top: 0;<br><br>right: 0;<br><br>bottom: 0;<br><br>left: 0;                                 |
| ------------ | ------------------------------------------------------------------------------------------ |
| -inset-0     | top: 0;<br><br>right: 0;<br><br>bottom: 0;<br><br>left: 0;                                 |
| inset-y-0    | top: 0;<br><br>bottom: 0;                                                                  |
| -inset-y-0   | top: 0;<br><br>bottom: 0;                                                                  |
| inset-x-0    | right: 0;<br><br>left: 0;                                                                  |
| -inset-x-0   | right: 0;<br><br>left: 0;                                                                  |
| top-0        | top: 0;                                                                                    |
| right-0      | right: 0;                                                                                  |
| bottom-0     | bottom: 0;                                                                                 |
| left-0       | left: 0;                                                                                   |
| -top-0       | top: 0;                                                                                    |
| -right-0     | right: 0;                                                                                  |
| -bottom-0    | bottom: 0;                                                                                 |
| -left-0      | left: 0;                                                                                   |
| inset-0.5    | top: 0.125rem;<br><br>right: 0.125rem;<br><br>bottom: 0.125rem;<br><br>left: 0.125rem;     |
| -inset-0.5   | top: -0.125rem;<br><br>right: -0.125rem;<br><br>bottom: -0.125rem;<br><br>left: -0.125rem; |
| inset-y-0.5  | top: 0.125rem;<br><br>bottom: 0.125rem;                                                    |
| -inset-y-0.5 | top: -0.125rem;<br><br>bottom: -0.125rem;                                                  |
| inset-x-0.5  | right: 0.125rem;<br><br>left: 0.125rem;                                                    |
| -inset-x-0.5 | right: -0.125rem;<br><br>left: -0.125rem;                                                  |
| top-0.5      | top: 0.125rem;                                                                             |
| right-0.5    | right: 0.125rem;                                                                           |
| bottom-0.5   | bottom: 0.125rem;                                                                          |
| left-0.5     | left: 0.125rem;                                                                            |
| -top-0.5     | top: -0.125rem;                                                                            |
| -right-0.5   | right: -0.125rem;                                                                          |
| -bottom-0.5  | bottom: -0.125rem;                                                                         |
| -left-0.5    | left: -0.125rem;                                                                           |
| inset-1      | top: 0.25rem;<br><br>right: 0.25rem;<br><br>bottom: 0.25rem;<br><br>left: 0.25rem;         |
| -inset-1     | top: -0.25rem;<br><br>right: -0.25rem;<br><br>bottom: -0.25rem;<br><br>left: -0.25rem;     |
| inset-y-1    | top: 0.25rem;<br><br>bottom: 0.25rem;                                                      |
| -inset-y-1   | top: -0.25rem;<br><br>bottom: -0.25rem;                                                    |
| inset-x-1    | right: 0.25rem;<br><br>left: 0.25rem;                                                      |
| -inset-x-1   | right: -0.25rem;<br><br>left: -0.25rem;                                                    |
| top-1        | top: 0.25rem;                                                                              |
| right-1      | right: 0.25rem;                                                                            |
| bottom-1     | bottom: 0.25rem;                                                                           |
| left-1       | left: 0.25rem;                                                                             |
| -top-1       | top: -0.25rem;                                                                             |
| -right-1     | right: -0.25rem;                                                                           |
| -bottom-1    | bottom: -0.25rem;                                                                          |
| -left-1      | left: -0.25rem;                                                                            |



# Visibility

[Docs](https://tailwindcss.com/docs/visibility)

Show or hide without affecting the layout of the document.

|           |                      |
| --------- | -------------------- |
| visible   | visibility: visible; |
| invisible | visibility: hidden;  |

# Z-index

[Docs](https://tailwindcss.com/docs/z-index)

Sets the z-order ("stack order") of a positioned element.

|        |                |
| ------ | -------------- |
| z-0    | z-index: 0;    |
| z-10   | z-index: 10;   |
| z-20   | z-index: 20;   |
| z-30   | z-index: 30;   |
| z-40   | z-index: 40;   |
| z-50   | z-index: 50;   |
| z-auto | z-index: auto; |

# Container Queries

[Docs](https://tailwindcss.com/docs/responsive-design)

New in v4: Built-in container query utilities — no plugin required.

|                   |                                  |                          |
| ----------------- | -------------------------------- | ------------------------ |
| @container        | container-type: inline-size;     | Define a query container |
| @container/{name} | container: {name} / inline-size; | Named container          |
| @3xs              | @container (width >= 16rem)      | 256px min-width          |
| @2xs              | @container (width >= 18rem)      | 288px min-width          |
| @xs               | @container (width >= 20rem)      | 320px min-width          |
| @sm               | @container (width >= 24rem)      | 384px min-width          |
| @md               | @container (width >= 28rem)      | 448px min-width          |
| @lg               | @container (width >= 32rem)      | 512px min-width          |
| @xl               | @container (width >= 36rem)      | 576px min-width          |
| @2xl              | @container (width >= 42rem)      | 672px min-width          |
| @3xl              | @container (width >= 48rem)      | 768px min-width          |
| @4xl              | @container (width >= 56rem)      | 896px min-width          |
| @5xl              | @container (width >= 64rem)      | 1024px min-width         |
| @6xl              | @container (width >= 72rem)      | 1152px min-width         |
| @7xl              | @container (width >= 80rem)      | 1280px min-width         |
| @max-sm           | @container (width < 24rem)       | Max-width query          |
| @max-md           | @container (width < 28rem)       | Max-width query          |
| @max-lg           | @container (width < 32rem)       | Max-width query          |
| @max-xl           | @container (width < 36rem)       | Max-width query          |
| @max-2xl          | @container (width < 42rem)       | Max-width query          |

# Color Scheme

[Docs](https://tailwindcss.com/docs/color-scheme)

New in v4: Utilities for controlling the color scheme hint for an element.

|                         |                           |
| ----------------------- | ------------------------- |
| color-scheme-normal     | color-scheme: normal;     |
| color-scheme-light      | color-scheme: light;      |
| color-scheme-dark       | color-scheme: dark;       |
| color-scheme-light-dark | color-scheme: light dark; |
| color-scheme-only-dark  | color-scheme: only dark;  |
| color-scheme-only-light | color-scheme: only light; |



# Font Family

[Docs](https://tailwindcss.com/docs/fonts)

Sets the font family.

|            |                                                                                                                                                                                                                |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| font-sans  | font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji"; |
| font-serif | font-family: Georgia, Cambria, "Times New Roman", Times, serif;                                                                                                                                                |
| font-mono  | font-family: Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;                                                                                                                             |

# Font Size

[Docs](https://tailwindcss.com/docs/text-sizing)

Sets the font size.

|           |                                                   |      |
| --------- | ------------------------------------------------- | ---- |
| text-xs   | font-size: 0.75rem;<br><br>line-height: 1rem;     | 12px |
| text-sm   | font-size: 0.875rem;<br><br>line-height: 1.25rem; | 14px |
| text-base | font-size: 1rem;<br><br>line-height: 1.5rem;      | 16px |
| text-lg   | font-size: 1.125rem;<br><br>line-height: 1.75rem; | 18px |
| text-xl   | font-size: 1.25rem;<br><br>line-height: 1.75rem;  | 20px |
| text-2xl  | font-size: 1.5rem;<br><br>line-height: 2rem;      | 24px |
| text-3xl  | font-size: 1.875rem;<br><br>line-height: 2.25rem; | 30px |
| text-4xl  | font-size: 2.25rem;<br><br>line-height: 2.5rem;   | 36px |
| text-5xl  | font-size: 3rem;<br><br>line-height: 1;           | 48px |
| text-6xl  | font-size: 3.75rem;<br><br>line-height: 1;        | 64px |
| text-7xl  | font-size: 4.5rem;<br><br>line-height: 1;         | 72px |
| text-8xl  | font-size: 6rem;<br><br>line-height: 1;           | 80px |
| text-9xl  | font-size: 8rem;<br><br>line-height: 1;           | 96px |

# Font Smoothing

[Docs](https://tailwindcss.com/docs/font-smoothing)

|                      |                                                                                 |
| -------------------- | ------------------------------------------------------------------------------- |
| antialiased          | -webkit-font-smoothing: antialiased;<br><br>-moz-osx-font-smoothing: grayscale; |
| subpixel-antialiased | -webkit-font-smoothing: auto;<br><br>-moz-osx-font-smoothing: auto;             |

# Font Style

[Docs](https://tailwindcss.com/docs/text-style)

|            |                     |
| ---------- | ------------------- |
| italic     | font-style: italic; |
| not-italic | font-style: normal; |

# Font Weight

[Docs](https://tailwindcss.com/docs/font-weight)

Sets the font weight.

|                 |                   |
| --------------- | ----------------- |
| font-thin       | font-weight: 100; |
| font-extralight | font-weight: 200; |
| font-light      | font-weight: 300; |
| font-normal     | font-weight: 400; |
| font-medium     | font-weight: 500; |
| font-semibold   | font-weight: 600; |
| font-bold       | font-weight: 700; |
| font-extrabold  | font-weight: 800; |
| font-black      | font-weight: 900; |

# Font Variant Numeric

[Docs](https://tailwindcss.com/docs/font-variant-numeric)

Utilities for controlling the variant of numbers.

|                    |                                           |
| ------------------ | ----------------------------------------- |
| normal-nums        | font-variant-numeric: normal;             |
| ordinal            | font-variant-numeric: ordinal;            |
| slashed-zero       | font-variant-numeric: slashed-zero;       |
| lining-nums        | font-variant-numeric: lining-nums;        |
| oldstyle-nums      | font-variant-numeric: oldstyle-nums;      |
| proportional-nums  | font-variant-numeric: proportional-nums;  |
| tabular-nums       | font-variant-numeric: tabular-nums;       |
| diagonal-fractions | font-variant-numeric: diagonal-fractions; |
| stacked-fractions  | font-variant-numeric: stacked-fractions;  |

# Letter Spacing

[Docs](https://tailwindcss.com/docs/letter-spacing)

Sets the spacing between letters.

|                  |                           |
| ---------------- | ------------------------- |
| tracking-tighter | letter-spacing: -0.05em;  |
| tracking-tight   | letter-spacing: -0.025em; |
| tracking-normal  | letter-spacing: 0;        |
| tracking-wide    | letter-spacing: 0.025em;  |
| tracking-wider   | letter-spacing: 0.05em;   |
| tracking-widest  | letter-spacing: 0.1em     |

# Line Height

[Docs](https://tailwindcss.com/docs/line-height)

Sets the line height.

|                 |                       |      |
| --------------- | --------------------- | ---- |
| leading-none    | line-height: 1;       |      |
| leading-tight   | line-height: 1.25;    |      |
| leading-snug    | line-height: 1.375;   |      |
| leading-normal  | line-height: 1.5;     |      |
| leading-relaxed | line-height: 1.625;   |      |
| leading-loose   | line-height: 2;       |      |
| leading-3       | line-height: .75rem;  | 12px |
| leading-4       | line-height: 1rem;    | 16px |
| leading-5       | line-height: 1.25rem; | 20px |
| leading-6       | line-height: 1.5rem;  | 24px |
| leading-7       | line-height: 1.75rem; | 28px |
| leading-8       | line-height: 2rem;    | 32px |
| leading-9       | line-height: 2.25rem; | 36px |
| leading-10      | line-height: 2.5rem;  | 40px |

# List Style Type

[Docs](https://tailwindcss.com/docs/list-style-type)

Sets the bullet style of a list.

|              |                           |
| ------------ | ------------------------- |
| list-none    | list-style-type: none;    |
| list-disc    | list-style-type: disc;    |
| list-decimal | list-style-type: decimal; |

# List Style Position

[Docs](https://tailwindcss.com/docs/list-style-position)

Sets the position of a list's bullets.

"list-style-position: outside;" copied into your clipboard

|              |                               |
| ------------ | ----------------------------- |
| list-inside  | list-style-position: inside;  |
| list-outside | list-style-position: outside; |

# Text Align

[Docs](https://tailwindcss.com/docs/text-alignment)

Sets the alignment of text.

|              |                      |
| ------------ | -------------------- |
| text-left    | text-align: left;    |
| text-center  | text-align: center;  |
| text-right   | text-align: right;   |
| text-justify | text-align: justify; |

# Text Color

[Docs](https://tailwindcss.com/docs/text-color)

Sets the text color.

|     |                  |                      |
| --- | ---------------- | -------------------- |
|     | text-transparent | color: transparent;  |
|     | text-current     | color: currentColor; |
|     | text-black       | color: #000000;      |
|     | text-white       | color: #ffffff;      |
|     | text-gray-50     | color: #F9FAFB;      |

# Text Decoration

[Docs](https://tailwindcss.com/docs/text-decoration)

Utilities for controlling the decoration of text.

|              |                                |
| ------------ | ------------------------------ |
| underline    | text-decoration: underline;    |
| overline     | text-decoration: overline;     |
| line-through | text-decoration: line-through; |
| no-underline | text-decoration: none;         |

# Text Decoration Style

[Docs](https://tailwindcss.com/docs/text-decoration-style)

Utilities for controlling the style of text decorations.

|                   |                                |
| ----------------- | ------------------------------ |
| decoration-solid  | text-decoration-style: solid;  |
| decoration-double | text-decoration-style: double; |
| decoration-dotted | text-decoration-style: dotted; |
| decoration-dashed | text-decoration-style: dashed; |
| decoration-wavy   | text-decoration-style: wavy;   |

# Text Decoration Thickness

[Docs](https://tailwindcss.com/docs/text-decoration-thickness)

Utilities for controlling the thickness of text decorations.

|                      |                                       |
| -------------------- | ------------------------------------- |
| decoration-auto      | text-decoration-thickness: auto;      |
| decoration-from-font | text-decoration-thickness: from-font; |
| decoration-0         | text-decoration-thickness: 0px;       |
| decoration-1         | text-decoration-thickness: 1px;       |
| decoration-2         | text-decoration-thickness: 2px;       |
| decoration-4         | text-decoration-thickness: 4px;       |
| decoration-8         | text-decoration-thickness: 8px;       |

# Text Underline Offset

[Docs](https://tailwindcss.com/docs/text-underline-offset)

Utilities for controlling the offset of a text underline.

|                            |                                   |
| -------------------------- | --------------------------------- |
| underline-offset-auto      | text-underline-offset: auto;      |
| underline-offset-from-font | text-underline-offset: from-font; |
| underline-offset-0         | text-underline-offset: 0px;       |
| underline-offset-1         | text-underline-offset: 1px;       |
| underline-offset-2         | text-underline-offset: 2px;       |
| underline-offset-4         | text-underline-offset: 4px;       |
| underline-offset-8         | text-underline-offset: 8px;       |

# Text Transform

[Docs](https://tailwindcss.com/docs/text-transform)

Utilities for controlling the transformation of text.

|                                |                             |
| ------------------------------ | --------------------------- |
| uppercase                      | text-transform: uppercase;  |
| lowercase                      | text-transform: lowercase;  |
| capitalize                     | text-transform: capitalize; |
| normal-case# Text Overflow<br> | text-transform: none;       |

# Text Overflow

[Docs](https://tailwindcss.com/docs/text-overflow)

Utilities for controlling text overflow in an element.

|               |                                                                               |
| ------------- | ----------------------------------------------------------------------------- |
| truncate      | overflow: hidden;<br><br>text-overflow: ellipsis;<br><br>white-space: nowrap; |
| text-ellipsis | text-overflow: ellipsis;                                                      |
| text-clip     | text-overflow: clip;                                                          |

