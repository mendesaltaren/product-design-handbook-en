# Figma

Figma allows us to work in a collaborative way, online and in real time. In addition, Figma allows us to perform the entire process we use in Sketch. It is a great alternative for performing ideation and definition exercises when the team cannot be present.

{% hint style="info" %}
The only reason why we use Sketch more than Figma is that with Sketch our process is much more automated thanks to plugins and more controlled versioning thanks to Abstract.
{% endhint %}

About how do we work in Figma, our process remains the same as in Sketch.

## Pages

Pages In our Figma files three kind of pages can be found, based on their content and current status:

**Pages in progress** ⚙️

The pages in progress are the ones you are currently working on. These are iterated on within the same frame or element.

It is important for us to identify pages that are not finished because we are still working on them. These are pages in which the content does not have to be perfect.

**Master pages** **✅**

The master pages contain the finished content. The content of this page must be perfect, have implemented styles, be made up of components and respect the defined spacing.

**Components page**

The components that make up the design system are located on this page.

{% hint style="info" %}
This is our way of organizing Figma, but it doesn't always have to be like this. This is our way of resolving conflicts about which pages are ready and which are being worked on.
{% endhint %}

In order to reflect these three types of pages and keep Figma files consistent within all projects, we require that all pages have a visual identifier, a numerical identifier, and a descriptive name for their content. 

This is their naming system:

```text
[Emoji] [id] [nombre página]
```

* Emoji: utilizamos ✅ para páginas master y ⚙️ para páginas en proceso.
* id: Are an incremental numerical identification with a 0 \(zero\) as a prefix.

An example would be:

* ✅ 01 Account
* ✅ 02 Catalog
* ✅ 03 Profile
* ⚙️ 03 Profile

## Frames

We group frames into user flows or user stories. Each row represents a possible path for the application or web being designed. At the beginning of each row, there is a frame containing the name and a description of the user flow being represented.

To name the frames we use an ID, which corresponds to that particular page, and a number that consists of the row number and the screen number.

```text
[id]_[row number][screen number]
```

* The id refers to the id of the page

  ✏️ If the page is 01 Account → id page: 01

* The row number refers to the user flow number in which we find ourselves.

An example would be:

First user flow → row number: 1   
Second user flow → row number: 2   
Third user flow → row number: 3

* The screen number is incremental from left to right.

  ✏️ If 01 02 03 04 05 06 07 08 09 10 11 12

An example would be:

For the user flows on page 01 Account:

```text
01_100 01_101 01_102 01_103

01_200 01_201 01_202 01_203 01_204

01_300 01_301 01_302 01_303
```

## Components

We use components to optimize and automate our work. Components make it easier for us to change multiple instances of the same element at the same time.

In Figma, components can belong to a file or to the Team Library. The Team Library is a collection of components shared by all people belonging to the team. In our case, the Team Library is shared by all the files by mendesaltaren.

The components in Figma are not the same as symbols in Sketch. Using a component creates a unique instance and not a copy of it. This allows the color and text properties of the elements that compose an instance to be changed, the only thing that cannot be modified is its position.

## Shared styles

**Color Styles**

A unique feature of Figma with regards to Sketch is that it does not have layer styles as such, but they are color styles only. Color styles can be applied to borders and fills in a layer as well as to text styles. This, for us, has two key advantages:

* We don't have to create so many layer styles, differentiating between when it's an outline or when it's a color fill.
* We don't have to create a text style for every color we use. We create some styles for our base text and on top of these, we apply defined color styles.

**Text Styles**

Text styles also differ as to how text styles are used in Sketch. In Figma for each style of text, only the size, box height and weight are reflected. The alignment can be modified.

This allows us to prevent having to create a different text style for each type of alignment \(left, center and right\). We only have to create one style and when we use it, we can freely modify it.

