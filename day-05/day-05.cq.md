---
coverImageBackgroundPosition: "50% 87%;"
---

# Day 04 - Text Editor - Setup & Tooling

Every mainstream computer comes with what is called a **text editor**.  What this means is that this program edits text without adding markup, i.e., in plain text.  Developers use text editors to assist in writing "code".

I>A **text editor** is not the same as a **word processor**.  A word processor, something like Microsoft Word or Open Office, adds styling to text (e.g., margins, font-size, bold, italic, etc.).  A text editor does not. When you write code, it's crucial that you *do not* use a word processor because the added styling will corrupt your code.

Technically, you could use your computer's default text editor to write code.  However, because developers use their text editors so much, it shouldn't surprise you to learn they have developed fancy, sophisticated text editors for the sole purpose of writing code.

For this blog series, I am going to suggest you use the **VSCode** text editor.  For several reasons: it's free, easy to navigate for beginners, and is a great first text editor that you can continue to use as you advance in web development.

W>I refuse to debate which text editor is better than another.  By suggesting folks start off with VSCode I am not making a statement that it is better than say Sublime or Atom. In fact, either of those would also be fine substitutes.  I'll leave the text editor debates to those also debating Windows vs. Mac.

#### Exercise: Setting up VSCode

1\. Download VSCode [here](https://visualstudio.microsoft.com/downloads/).

![](public/assets/vs-1.png)

You'll want to select the Free version which you can find under "Visual Studio Code."  See the pink box in the screenshot.  Also, make sure you are downloading the correct version.  If you are on Windows you will need to select "Windows," and not "macOS," as I have here.

2\. Once you click download, a zip file will start downloading.  Open it when it's done.  Once downloaded, move the VSCode application to your Applications folder.

3\. Open VSCode like you would any other Application.

![](public/assets/vs-2.png)

4\. Next, let's open a simple text file using VSCode.

Download the following [`test-file.txt`](public/src/1-setup/test-file.txt).

Back in VSCode, open the file you just downloaded by clicking File -> Open, and select the file `test-file.txt`.

![](public/assets/6-file-open.png)

6\. Once open, you should see something like the following screenshot (your theme/look is likely different than mine).  

![](public/assets/vs-5.png)

7\. One helpful thing about text editors like VSCode is that they give line/row numbers.  We will use these in our examples to describe where on the document you should look.  So for example, if I say "on row 3", I mean the row with the sloth fact.

![](public/assets/vs-6.png)

Use the keyboard shortcut `control + g` to navigate to a specific row. Once you hit that command, you'll be asked to type in a line number.  Here I typed in 2, and you can see the line 2 in highlighted is light-yellow.

![](public/assets/vs-7.png)

You don't have to use this command, but it's helpful if you have a big file and want to navigate to a specific line/row number quickly. Try it out and see if you find it useful.

8\. One last, "how to" that we should know for VSCode is saving.  Saving here is just like saving in any other application.  You can go to File -> Save, or as I prefer, use a keyboard shortcut `command + s` (control for Windows users).

By the end of these 30 days, you'll have more practice using VSCode and should get more comfortable using it. VSCode has a lot more bells and whistles, and if you'd like to learn more about them, I recommend VSCode's ["Getting Started" videos](https://code.visualstudio.com/docs/introvideos/basics).

That's it for Setup & Tooling.  Tomorrow, we'll start looking at the foundational language of the web, HTML. 