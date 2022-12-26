README is what attracts developers/visitors to view your project. If your README contains just plain text, AHHH, it’s not convincing. It is like subject books as you grow up; with less pictures, small font, large paras and no interest. I guess it is not just me who used to search for pictures in the book to estimate how interesting it would be, how much I would read it in future, or if I would even touch it.

If I write this blog without any pictures🖼️, same sized font🔤, no separations, no humor🤡, no anecdotes; in short no interest❌; I am technically writing it in vain. It’s not gonna get sold and I am gonna remain poor. POOR ME😭. I don’t know how much interesting I can make this blog but I hope it can help you.

README is the face of your project and you need to apply the best makeup on to make it look sufficiently presentable so you won’t loose YOUR FACE. So, let’s start and get to know what all we have for the MAKEUP and how to apply it.

Makeup Kit includes :-

    Headings
    Linebreaks
    Emphasis
    Blockquotes
    Don’t render Code
    Lists — ordered and unordered
    Horizontal rules
    Links
    Images/GIF
    Video
    Labels
    Tables
    Task List
    Add Color
    Write text as code
    Add Emoji

All in one kit. No better place to go. Let’s begin
1. Headings

Same as in HTML, here you have 6 headings.

Code :-

    # Heading1
    ## Heading2
    ### Heading3
    #### Heading4
    ##### Heading5
    ###### Heading6

Headings

A line is given by default for Heading1 and Heading2. Others are without it.
2. Line Breaks

For a line break or writing to a new line you can either opt the markdown way or the HTML way. Both works fine.

Markdown :- To create a line break, end a line with two or more spaces, and hit enter.

    Markdown Way
    of breaking

Sorry, they won’t allow more than 1 space here so copy pasting the above code won’t work for you.

HTML :- Just add the break tag (<br>)

    HTML way <br>
    of breaking

Line Breaks
3. Emphasis

Bold and Italic are the 2 emphasis modes. It adds a little weight to your monotonous text.

Bold :- Doubles are for bold

    **Bold**
    __Bold__

Italic :- Singles are for italic

    *Italic*
    _Italic_

What if we want both, a HYBRID ?

    ***Hybrid***
    ___Hybird___
    **_Hybrid_**
    *__Hybrid__*

4. Blockquotes

Blockquotes are quotes that are set off from the main text as a paragraph, or block of text.

Code :- (The > on 2nd line is for an empty line in output)

    > This is a blockquote
    >
    > This is next line

Nested Blockquote

    > This is main Blockquote
    > >This is nested Blockquote
    > >
    > >Let’s get out of nested
    >
    > Let’s get out of main

5. Code

“Don’t render it. I said DON’T. Keep it as a code.”

Write the code and give a tab to all, i.e. 4 spaces. Indent them by 4 spaces to keep them as a normal text. If you don’t indent it, it will be read as an HTML block.

Code :- (More than 1 space not allowed here)

    <html>
    <body>
    <p>Let’s keep it as a code block and not render it for once</p>
    </body>
    </html>

6. Lists

Lists are very necessary for README like when you want to list the features, or languages used, etc.

Unordered List :-

    * Item1
    * Item2
    * Item3

    - Item1
    - Item2
    - Item3

Ordered List :-

    1. Item1
    2. Item2
    3. Item3

7. Horizontal Rules

To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___).

    ---

    ****

    _______

8. Links

To create a link, enclose the link text in brackets and then follow it immediately with the URL in parentheses. You can also simply copy paste a link.

    [Link to Portfolio Website](https://gaganpreetkaurkalsi.netlify.app/)

Output

Link with title :-

    [Link to Portfolio Website](https://gaganpreetkaurkalsi.netlify.app “My Portfolio Website”)

When you hover over, the title is shown
9. Images

Images are very important to make your README attractive.

To place an image,

    upload it to your repository
    mention its path in the below given markdown

    ![Alt](path to img)

    ![Image](/component-library/images/website.svg)

GIF — You can also upload a GIF. Just mention its link in place of image link. The syntax remains same.

    ![Main](https://media.giphy.com/media/wKoPDy4mp8Lr6IJ9ce/giphy.gif)

website.svg displayed in README

You can also drag and drop an image in the README. This feature has been added recently.
Sorry for the poor quality
10. Video

Same as Image you can upload a video to your README. Make a short video of your project and paste it to gain more viewers.
Drag and Drop. It’s as simple as that
11. Labels

Here is code to a few labels below. Feel free to use. Mention your Github Username and repository name in the space mentioned.

    ![GitHub all releases](https://img.shields.io/github/downloads/{username}/{repo-name}/total)
    ![GitHub language count](https://img.shields.io/github/languages/count/{username}/{repo-name})
    ![GitHub top language](https://img.shields.io/github/languages/top/{username}/{repo-name}?color=yellow)
    ![Bitbucket open issues](https://img.shields.io/bitbucket/issues/{username}/{repo-name})
    ![GitHub forks](https://img.shields.io/github/forks/{username}/{repo-name}?style=social)
    ![GitHub Repo stars](https://img.shields.io/github/stars/{username}/{repo-name}?style=social)

Output Labels

For more such labels visit https://shields.io/
12. Table

Well I haven’t used them yet in any of my projects but maybe you were just looking for it and I saved you.

You can create tables with pipes | and hyphens -. Hyphens are used to create each column's header, while pipes separate each column. There must be at least three hyphens in each column of the header row. Copy pasting code won't work.

    | Header1 | Header2 | Header3 |
    | — — — | — — — — — -| — — — — — |
    | R1C1 | R1C2 | R1C3 |
    | R2C1 | R2C2 | R2C3 |

Table

Table with Alignment :-

To align items :-

    Left Align — :---
    Center Align — :---:
    Right Align — ---:

    | Header1 | Header2 | Header3 |
    | :---- | :----: | ----: |
    | R1C1 | R1C2 | R1C3 |
    | R2C1 | R2C2 | R2C3 |

Table with Alignment

Note :- Copy pasting codes won’t work. I tested it. Just write on your own and it will be fine
13. Task List

Just another thing you can try to fit in somewhere in your README.

    - [x] Write a blog
    - [x] Make it interesting
    - [ ] Publish it

Task list
14. Add COLOR

Don’t know what this is or how I can use it, but I came through this when searching for how I can add colors. I don’t think GOOGLE got me. But as I am documenting all, why leave this behind. No Prejudice.

    ```diff
    - This is a red colored line
    + This is a green colored line
    @@ This is a purple colored line @@
    ```

Output
15. Write text as CODE

Do you wanna put a gray background to your text and make it appear as a code segment. This is what you need.

    `Hello This is a code`

    `` Using `single back ticks` inside double back ticks``

Output
16. Add Emoji 😊

Last but not the least, do you wanna add some emojis to your README. Here is how to do it.

    Go to https://emojipedia.org/
    Search for the perfect emoji
    Copy and paste it in the README

Copy from here

I know many of you might know this. But still for those who don’t. It is cool.

I guess that’s it. I have documented all the useful markdowns which you can add to your README. Make it beautiful and make every customer fall in love🥰 with it. Remember it is the FACE. Put makeup in a decent way.

Here is the link to one of my README which I created recently. I seriously couldn’t remember how to write it. As a result, I thought of writing a blog so if future me somehow forgets again it is just a copy, paste and an enter away. If you like it remember to give repo a star⭐.

Here are some links where you can reach me

Email — gagansinghkalsi4126@gmail.com

Github — https://github.com/GaganpreetKaurKalsi

I hope I was of any help and able to reduce a little of your efforts by putting everything at one place. If you like it, please give a clap👏 and I will give a pat on my back.

Thank You!

See you all! Bye 👋
