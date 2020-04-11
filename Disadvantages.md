

# References

## Why need references?

In [incremental reading](https://help.supermemo.org/wiki/Glossary:Incremental_reading), you always need to quickly recover the context of a question or a piece of text. The easiest way to recover context quickly is via references. References propagate from [element](https://help.supermemo.org/wiki/Glossary:Element) to element as you produce [extracts](https://help.supermemo.org/wiki/Glossary:Extract) and [cloze deletions](https://help.supermemo.org/wiki/Glossary:Cloze_deletion). With all [child elements](https://help.supermemo.org/wiki/Glossary:Child) produced from a given text marked with references, you would never need to worry about losing the context of the question.

For example:

**Q**: He was born in **[...](year)**

cannot be answered without the context. However, the following question is already easier to understand:

**Q**: He was born in **[...](year)**

------

*#Title: Barrack Obama
\#Source: Wikipedia*

To speed up learning, in the incremental reading process, the above question should naturally be replaced with:

**Q**: Obama was born in **[...](year)**

or

**Q**: Obama was born in **[...](year)**

------

*#Title: Barrack Obama
\#Source: Wikipedia*

References are not stored in HTML files that hold your articles but in a reference [registry](https://help.supermemo.org/wiki/Glossary:Registry) (i.e. in a separate database). The reference registry does not hold the text of references either. All reference texts are held in the text [registry](https://help.supermemo.org/wiki/Glossary:Registry) and are available for global text searches. In earlier versions of SuperMemo, each text would keep its own copy of references. In newer SuperMemos, [elements](https://help.supermemo.org/wiki/Glossary:Element) keep only pointers to reference [registry](https://help.supermemo.org/wiki/Glossary:Registry), which in turn keeps pointers to individual text fields in the text registry. As a result, many [elements](https://help.supermemo.org/wiki/Glossary:Element) can hold the same reference, and many references can hold the same text. This results in a significant saving in space in your [collection](https://help.supermemo.org/wiki/Glossary:Collection). More importantly, you can update the reference in a single [element](https://help.supermemo.org/wiki/Glossary:Element) and see the change show in all [elements](https://help.supermemo.org/wiki/Glossary:Element) using the same reference. This way, you do not need to waste time on search&replace to correct a single misspelling or reference inaccuracy that propagated to many [elements](https://help.supermemo.org/wiki/Glossary:Element).

## Example

If you select the title of the source article and press *Alt+T* (**[Reference](https://help.supermemo.org/wiki/Component_menu#Reference) : Title** on the HTML [component menu](https://help.supermemo.org/wiki/Component_menu)), each [extract](https://help.supermemo.org/wiki/Glossary:Extract) will be marked by the title of the source article. If you use **[Edit](https://help.supermemo.org/wiki/Edit_menu) : [Web import](https://help.supermemo.org/wiki/Web_import) : All**, your articles will be provided with basic references (such as *#Title*, *#Link*, *#Date*, etc.). If you need more context (e.g. to add the author, the journal, etc.), you can use the reference link button ([![SuperMemo: Reference button on the navigation bar in the element window](https://help.supermemo.org/images/9/9e/Reference_button.gif)](https://help.supermemo.org/wiki/File:Reference_button.gif)) on the [navigation bar](https://help.supermemo.org/wiki/Navigation_bar) to jump to the source article from which the [extract](https://help.supermemo.org/wiki/Glossary:Extract) was produced. On the parent article, that button will lead you to the original link on the net.

[![SuperMemo: An extract produced from an article about the greenhouse effect (references (in pink) at the bottom are added automatically)](https://help.supermemo.org/images/thumb/f/f5/Incremental_reading_Extract.jpg/800px-Incremental_reading_Extract.jpg)](https://help.supermemo.org/wiki/File:Incremental_reading_Extract.jpg)

> ***Figure:** Typical snapshot of [incremental reading](https://help.supermemo.org/wiki/Glossary:Incremental_reading). While learning about the greenhouse effect, the student extracts the fragment saying that "An ideal thermally conductive [blackbody](https://en.wikipedia.org/wiki/Blackbody) at the same distance from the Sun as Earth would have a temperature of about 5.3 °C. However, because Earth reflects about 30%[[5](https://en.wikipedia.org/wiki/Greenhouse_effect#cite_note-5)][[6](https://en.wikipedia.org/wiki/Greenhouse_effect#cite_note-6)] of the incoming sunlight, this idealized planet's [effective temperature](https://en.wikipedia.org/wiki/Effective_temperature) (the temperature of a blackbody that would emit the same amount of radiation) would be about −18 °C.[[7](https://en.wikipedia.org/wiki/Greenhouse_effect#cite_note-7)][[8](https://en.wikipedia.org/wiki/Greenhouse_effect#cite_note-8)] The surface temperature of this hypothetical planet is 33 °C below Earth's actual surface temperature of approximately 14 °C.[[9](https://en.wikipedia.org/wiki/Greenhouse_effect#cite_note-9)]. The mechanism that produces this difference between the actual surface temperature and the effective temperature is due to the atmosphere and is known as **greenhouse effect**". The extracted fragment will inherit illustrations placed on the right, as well as article [references](https://help.supermemo.org/wiki/References). The student can move on to reading another article by pressing Enter. The picture on the right is stored locally in the image [registry](https://help.supermemo.org/wiki/Glossary:Registry) (on the user's hard disk) and can be reused to illustrate other articles or questions.*

## Reference system highlights

- To mark texts as reference fields use the **[Reference](https://help.supermemo.org/wiki/Component_menu#Reference)** submenu on the HTML [component menu](https://help.supermemo.org/wiki/Component_menu) (e.g. **[Reference](https://help.supermemo.org/wiki/Component_menu#Reference) : Select** or *Alt+Q*)
- Reference fields *#Article*, *#Parent* and *#Concept group* are added automatically and are not stored in the reference [registry](https://help.supermemo.org/wiki/Glossary:Registry). These fields are not generated in [elements](https://help.supermemo.org/wiki/Glossary:Element) that have no other reference fields defined
- References marked with *Alt+Q* options show up in the reference field and can be deleted from the text's body (if no longer needed)
- Hover your mouse over the **Reference link** button ([![SuperMemo: Reference button on the navigation bar in the element window](https://help.supermemo.org/images/9/9e/Reference_button.gif)](https://help.supermemo.org/wiki/File:Reference_button.gif)) on the [navigation bar](https://help.supermemo.org/wiki/Navigation_bar) to quickly see the reference in longer extracts.
- From the user's point of view, there is a little difference in the way the references are handled as compared with earlier SuperMemos. SuperMemo 2008 or later differentiates between the following 2 types of references edits:
  - **local edits** that affect only the present [element](https://help.supermemo.org/wiki/Glossary:Element) and create a new reference record vs.
  - **global edits** which change the original reference in all the elements that use it.



- Note that all [extracts](https://help.supermemo.org/wiki/Glossary:Extract) generate [elements](https://help.supermemo.org/wiki/Glossary:Element) that are [children](https://help.supermemo.org/wiki/Glossary:Child) of the original article. If you have problems with recalling the original context of a fragment, you can always call it back by pressing the **Parent** button on the [navigation bar](https://help.supermemo.org/wiki/Navigation_bar). You can also use the **Reference link** button ([![SuperMemo: Reference button on the navigation bar in the element window](https://help.supermemo.org/images/9/9e/Reference_button.gif)](https://help.supermemo.org/wiki/File:Reference_button.gif)) to get to the source article, or, if you have already reached it, to get to the original article on the web.

- If you choose an empty selection for the *#Date* reference, you will mark the text with the current date and time stamp

- AND-Search in SuperMemo works on texts, not on [elements](https://help.supermemo.org/wiki/Glossary:Element). This means that reference texts do not take part in AND-Search for the main body of text. This may result in false misses. In SuperMemo, texts and individual reference fields are all treated as separate texts and are all searched independently

- Formatting of references can be changed via stylesheets

- Converting HTML to plain text does not affect the formatting of references (i.e. plain text entries can have their references formatted by a stylesheet)

- You can edit references in the reference area or in a dedicated window that you can open by choosing **[Reference](https://help.supermemo.org/wiki/Element_menu#Reference) : Edit** from the [element menu](https://help.supermemo.org/wiki/Element_menu). You only need to use legal reference field tags at the beginning of each reference line (e.g. *#Author:*). If SuperMemo is not sure if your changes should apply to the current [element](https://help.supermemo.org/wiki/Glossary:Element) only, or to all elements that use the reference, it will ask you

- You can quickly modify (i.e. set, merge, and delete) the references across a number of

   

  elements

  . To do that, open them in the

   

  element browser

  , right-click your mouse and choose:

  - **[Process browser>](https://help.supermemo.org/wiki/Subset_operations) : [Reference](https://help.supermemo.org/wiki/Subset_operations#Reference) : Set reference** to set the same reference to a subset of elements,
  - **[Process browser>](https://help.supermemo.org/wiki/Subset_operations) : [Reference](https://help.supermemo.org/wiki/Subset_operations#Reference) : Merge reference** to add reference fields to a subset of elements,
  - **[Process browser>](https://help.supermemo.org/wiki/Subset_operations) : [Reference](https://help.supermemo.org/wiki/Subset_operations#Reference) : Delete reference** to remove reference fields from all elements in the [subset](https://help.supermemo.org/wiki/Glossary:Subset)

- References no longer clutter your HTML files. In the past, the size of references would often be greater than the length of the text itself

- Reference [registry](https://help.supermemo.org/wiki/Glossary:Registry) keeps the references (see below), and their individual text fields are stored in the text registry

- References are added to HTML texts at load time, so that you can still have references located at the bottom of your texts as in earlier versions of SuperMemo

- Adding an existing reference to an [element](https://help.supermemo.org/wiki/Glossary:Element) (e.g. with **[Reference](https://help.supermemo.org/wiki/Element_menu#Reference) : Link** from the [element menu](https://help.supermemo.org/wiki/Element_menu)) does not add to the size of the [collection](https://help.supermemo.org/wiki/Glossary:Collection)

**Important!** **Do not add your own non-reference texts below the horizontal bar marking the reference area**. All reference field area is owned by SuperMemo. Any modifications to that area will be treated as changes to reference fields. Changes that do not conform with reference field formatting will be discarded without warning.

[![SuperMemo: References help you quickly recover the context of a given element as well as track its source and build a list of citations (in the picture: blue marks an incremental reading extract, yellow marks a search string (i.e. GABA-ergic), while pink marks the reference field, which will propagate to all children elements (extracts and clozes))](https://help.supermemo.org/images/thumb/5/5b/References.jpg/800px-References.jpg)](https://help.supermemo.org/wiki/File:References.jpg)

> ***Figure:** [References](https://help.supermemo.org/wiki/References) help you quickly recover the context of a given [element](https://help.supermemo.org/wiki/Glossary:Element) as well as track its source and build a list of citations. In the picture, an [extract](https://help.supermemo.org/wiki/Glossary:Extract) from an article on sleep and dreaming. Blue marks an extract produced from the presented text. Yellow marks the search string (i.e. REM-on cells) that was used in **[Search](https://help.supermemo.org/wiki/Search_menu) : [Find elements](https://help.supermemo.org/wiki/Find_elements)** (Ctrl+F) to find all the [elements](https://help.supermemo.org/wiki/Glossary:Element) (including this one) containing the string. Pink marks the reference area (consisting of the \*#Title\*, \*#Author\*, \*#Date\*, \*#Source\*, \*#Article\*, \*#Parent\*, and \*#Concept group\* fields), which will propagate to all [children elements](https://help.supermemo.org/wiki/Glossary:Child) ([extracts](https://help.supermemo.org/wiki/Glossary:Extract) and [clozes](https://help.supermemo.org/wiki/Glossary:Cloze_deletion)) generated from this [element](https://help.supermemo.org/wiki/Glossary:Element).*

[![SuperMemo: References are kept in a dedicated registry while their individual text fields (e.g. title, author, date, source, etc.) are stored in the text registry, and thus are available for global text searches](https://help.supermemo.org/images/thumb/7/74/Reference_registry.jpg/800px-Reference_registry.jpg)](https://help.supermemo.org/wiki/File:Reference_registry.jpg)

> ***Figure:** [References](https://help.supermemo.org/wiki/References) are kept in a dedicated [registry](https://help.supermemo.org/wiki/Glossary:Registry) while their individual text fields (e.g. \*#Title\*, \*#Author\*, \*#Date\*, \*#Source\*, etc.) are stored in the text registry, and thus are available for global text searches. In the picture, reference [registry](https://help.supermemo.org/wiki/Glossary:Registry) holds 71,791 members. Those highlighted in yellow are [references of downloaded images](https://help.supermemo.org/wiki/References#Image_references). The remaining references describe imported articles. The selected Quantum Biology reference describes and article imported from [Nature Physics](http://www.nature.com/nphys/index.html) in Feb 2013. The element list panel (bottom-right) displays [topics](https://help.supermemo.org/wiki/Glossary:Topic) generated from that article. All those [topics](https://help.supermemo.org/wiki/Glossary:Topic) share the same reference.*

## Editing references

You an use **Reference: Edit** in [SuperMemo Commander](https://help.supermemo.org/wiki/SuperMemo_Commander), however, you can also edit references in the reference area (which is pink in the default stylesheet). You can safely delete reference fields, but you need to decide if that change should be local (for that [element](https://help.supermemo.org/wiki/Glossary:Element) only) or global (for all elements using this reference). You will not be able to delete *#Article*, *#Parent:* or *#Concept group* fields because they are added automatically to the reference section (i.e. they are not part of the reference itself). You can freely change the text of references. Illegal changes are all changes that do not comply with the reference format, e.g. lines that do not start with reference field tags, or lines that start with unknown reference field tags (e.g. *#Country*). If you are unsure how this process works, import a single article from [Wikipedia](http://en.wikipedia.org/) to a newly created [collection](https://help.supermemo.org/wiki/Glossary:Collection), create some [extracts](https://help.supermemo.org/wiki/Glossary:Extract) and play with editing to see how references are processed.

## Image references

Image references are created automatically when importing from the web or from an HTML document. In SuperMemo 16, unless you imported images with whole references pages, duplicate detection would depend on image names. If you renamed your images to make reuse easy, duplicate detection wouldn't work. This changed with SuperMemo 17. URLs are kept in the text [registry](https://help.supermemo.org/wiki/Glossary:Registry) which can accept a degree of "garbage" as text reuse is automatic. The adopted complex solution may make SuperMemo a bit slower when importing images from imported articles or when importing pictures from the web. However, your [collection](https://help.supermemo.org/wiki/Glossary:Collection) is unlikely to swell with multiple image duplicates. Duplicate imports are automatically prevented and the imported image is replaced with the stored original (wiki thumbs are replaced with their high-resolution originals).

Image references allow of searching for picture names along other texts in [elements](https://help.supermemo.org/wiki/Glossary:Element) with **[Edit](https://help.supermemo.org/wiki/Edit_menu) : [Find elements](https://help.supermemo.org/wiki/Find_elements)** (*Ctrl+F*).

You can find image references in the reference [registry](https://help.supermemo.org/wiki/Glossary:Registry) (choose **[Search](https://help.supermemo.org/wiki/Search_menu) : [References](https://help.supermemo.org/wiki/Search_menu#References)** from the [main menu](https://help.supermemo.org/wiki/Main_menu)). Alternatively, you can first locate the image via the image registry (**[Search](https://help.supermemo.org/wiki/Search_menu) : Images** from the [main menu](https://help.supermemo.org/wiki/Main_menu)), and choose **[View](https://help.supermemo.org/wiki/Registry_menu#View) : Reference** from the [registry menu](https://help.supermemo.org/wiki/Registry_menu) (available with a right-click).

In the reference [registry](https://help.supermemo.org/wiki/Glossary:Registry), to view the image related to a given reference, click **Go to** at the bottom of the window.

To see all [elements](https://help.supermemo.org/wiki/Glossary:Element) associated with a given image/reference, click **List** at the bottom of either registry (image or reference).
