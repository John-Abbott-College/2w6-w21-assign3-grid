# Assignment 3 - Grid & Cloning

March 2021 - 420-2W6 - User Interfaces



**Worth**:  9% of your total grade (from the ‘Assignments’ evaluation component).

**Due**:  Saturday, April 10th, 2021, at midnight (end-of-day).

**Hand In**:  A .txt file in Moodle (under Assignment 3) containing your project’s Git commit     Id code (from your private GitHub repository).

**Late Policy**:  3 cumulative “late days” during the course. Any work submitted after the 3 “late     days” have been used will not be graded.

------



## Objectives

- To integrate Git and GitHub into your workflow and assignment submission.
- To clone a professional website using Grid and Flexbox.
- To create a responsive webpage for mobile, tablet and desktop formats using a **mobile-first approach**.



## Context

In this assignment you will clone the [Pexels - Video website](https://www.pexels.com/videos/) using a combination of Grid and Flexbox for the layout. Observing and mimicking is an important method of learning design skills.

It is important to formulate a plan before jumping into the implementation, so you will be asked to visually break-down the layout of your website.



## Part 1: Container Layout Planning (2 %)



In this assignment you will clone the [Pexels - Video website](https://www.pexels.com/videos/) using a combination of Grid and Flexbox for the layout.



Visually layout the relationships between grid containers and their grid items for **each section of the desktop website that uses grid**. Images for each section are provided in the **layouts folder**.



Clearly identify the following:



1. For **Grid elements only**:

   1. Grid containers should be identified with a solid colored border.
   2. Grid items should be identified with a dashed black border.
   3. A Grid item can also be a Grid container and will have a colored dashed border.

2. For each Grid container:

   1. Include a legend listing how the columns and rows will be setup.

3. Once you are done, provide your images in **one of the following formats**:

   1. A png image for each section using grid.
   2. A pdf file for each section using grid.
   3. All diagrams in a single Draw.io file.

   <br>

   ![img](https://docs.google.com/drawings/u/0/d/sx-HyyCHPFLQO9Q088GyCGw/image?w=135&h=221&rev=37&ac=1&parent=1PYS_r-FEFzrhmapXaG-kGCN9HdFv42ptVnStxKFljpc)

<br>

You can choose to use any visual diagramming tool you would like (such as PowerPoint, Google Slides, Draw.io, LucidChart, etc).



[**Annex B**](https://docs.google.com/document/d/1PYS_r-FEFzrhmapXaG-kGCN9HdFv42ptVnStxKFljpc/edit#heading=h.j09ppfgf3j0r) describes an example if you were cloning [YouTube’s homepage](https://www.youtube.com/) with the viewport between 870px and 1120px width.



## Part 2: Cloning (4 %)

You will implement the [Pexels Video website](https://www.pexels.com/videos/) using Grid and Flexbox for layout and positioning. Please note that it does not need to be a perfect copy, however, it should get very close.



There are two minor modifications from the official site, which are:

- The top navbar must be constantly shown at the top and should not change colors;
- The video Grid must only contain the first 3 rows.



You should simplify your website so that you **don’t use any JavaScript, CSS animations or transitions.**

Additional information for the **navbar** and the **gallery** sections are described below.



### Navbar

In the original website the navbar is initially transparent and then becomes dark-blue as you scroll down (see animation below).



For this assignment **the navbar must be constantly shown at the top of the viewport and should not change colors.** Use the navbar as shown after scrolling down (see image below).

<br>

![img](https://lh3.googleusercontent.com/ci-N4TXa3nJwCdmXpx6E0REhfXgc8o3YD4Oe1mWgAbtmnBsGdP8v7ra-_nFvWVFz8TWSmR-GhVNKLExrsGaFZV4isuy4fEXhxDZ2b6xCwHGnm5iA6Ue8jhSVg5hoSwfs1BBYefBN)

<br>

We haven’t yet covered html forms in the course. In order to add the search bar to the navbar and hero section, [use the code in this CodePen as a reference](https://codepen.io/maujac/pen/QWjjjda).



**Clicking on the logo or any navigation link should take the user to the official Pexels site.**



### Video Grid Gallery

You must implement a video gallery using CSS Grid.

All the visual assets required to implement this page are provided in [**Annex A**](https://docs.google.com/document/d/1PYS_r-FEFzrhmapXaG-kGCN9HdFv42ptVnStxKFljpc/edit#heading=h.usi3rwel4yi4)



The requirements for this section are:



- Unlike the original site, the videos in the gallery should not play on hover, they will be static images.
- The “Trending” dropdown menu should be present but does not need to open/activate.
- You are required to **include only the top 3 rows.**
- At the desktop format your gallery should have the structure illustrated below. Notice how one image spans 2 rows.
- When the user clicks on the play icon, they should be taken to the official video page. 

<br>

![img](https://lh6.googleusercontent.com/y5iQumOhO5j5W62H6_QDIeJ4u0kdzW3kw7m2_MYowQENJ98UE6U0bCzLvnnqC01iNZGy4_n0kGjEGP4zeiGLQ8u2m96kkRr16oEIwMaccfVkfN6e1d_8zBsb-P2wElxSqWaqEQfo)

<br>

## Part 3: Responsive Design (3 %)

Your website should be fully responsive and you must **use a mobile-first approach**.



Based on the original website, implement the following breakpoints:



- **Mobile portrait:** 594 px and below - Single column, hamburger menu.
- **Tablet:** 595px to 1076px - Double columns, three-dot menu, Join button.
- **Desktop:** 1077px and above - Three columns, full navbar.



(note: there are two additional breakpoints in the original site but you don’t need to add them)

<br>

![img](https://lh3.googleusercontent.com/7u7Zjpf4vujoqpqGRsld8ASS6RE_iyjqbQTojEIZwiGLePrlMsBmkbfRpgqub-1Dy-S6snysUUDuOulxMxinzoUNKSK7vzefz0cuVR9ecUS2jEaYFzYEeyY3RbMts4Nouipl9zZp)

<br>




## Bonus: card details on hover (+1%)



For each video card in the gallery, an on-hover event should trigger the following:



- Make the card details appear. The details should include:

- - Author’s name and circle avatar (you can mock the avatar);
  - The “plus” and the “heart” svg icons;

- Display a tooltip text with the image description

- No animations, transitions, or JavaScript should be used;



You can get all the information required from the original video’s Pexels page. The URL is included in the assets list. See the gif below for a demonstration:

<br>

![img](https://lh4.googleusercontent.com/V46avL1Oj_lX2DFyFBrq9By_YXYTBChCApHwdipsL137snnujjwWWZilf9BR3uIETyLOmOxbAJvCdsCvcRZItUDokJmva3rKiTMnno3OtMo0oDkzhmRrArLB9ruAkLcLF9v_RNDk)

<br>

## Submission

You must submit **a single .txt file in Moodle**. In the .txt file please include:



- The commit id code (short version) to be grades and nothing else.



## Annex A: Visual Assets

Below is a list of the visual assets required for the project.

**For assets not listed, use the Dev Tools to get the source URL from the original site.**



### Navbar

The navbar uses svg images for the logo and icons. You can treat svg images the same way you would handle an `<img>` element, however, their size must be explicitly defined.

You can [copy-paste the svg images from this CodePen](https://codepen.io/maujac/pen/rNOOxYx).



Note: the original website imports svg images using the font-awesome service. You can use it if you would like. If you are interested you can learn more about it [here](https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use) or on the course notes.



### Hero Section

[Background poster (the static version of the video)](https://www.pexels.com/assets/videos/free-videos-7daa2ef41a140f70c757ce91913a4ecb90570b7d7cd2b401bae868350e02c83a.jpg)

[Background video in mp4 format](https://static.pexels.com/lib/videos/free-videos.mp4)

[Background video in webm format](https://static.pexels.com/lib/videos/free-videos.webm)

**Hint 1:** add the static poster first as a placeholder, then replace it with the video.

**Hint 2:** use the Dev Tools to see how the original website plays the video in the background.



### Video Gallery

[Image A (thunderbolt)](https://images.pexels.com/videos/855936/free-video-855936.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500) - full video [link](https://www.pexels.com/video/thunderbolt-855936/)

[Image B (time lapse video of sky)](https://images.pexels.com/videos/1869959/free-video-1869959.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500) - full video [link](https://www.pexels.com/video/time-lapse-video-of-sky-1869959/)

[Image C (vast area of dry land)](https://images.pexels.com/videos/1572321/free-video-1572321.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500) - full video [link](https://www.pexels.com/video/vast-area-of-dry-land-1572321/)

[Image D (motor vehicle traffic on a mountain road)](https://images.pexels.com/videos/3676936/pexels-photo-3676936.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500) - full video [link](https://www.pexels.com/video/an-elevated-highway-in-the-mountain-valley-in-hawaii-3629511/)

[Image E (woman holding her dog)](https://images.pexels.com/videos/2796078/free-video-2796078.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500) - full video [link](https://www.pexels.com/video/woman-holding-her-dog-2796076/)

[Image F (underwater bubbles)](https://images.pexels.com/videos/857131/free-video-857131.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500) - full video [link](https://www.pexels.com/video/underwater-bubbles-857131/)

[Image G (water crashing over the rocks)](https://images.pexels.com/videos/1093662/free-video-1093662.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500) - full video [link](https://www.pexels.com/video/water-crashing-over-the-rocks-1093662/)

[Image H (people traveling in the desert)](https://images.pexels.com/videos/1739011/free-video-1739011.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500) - full video [link](https://www.pexels.com/video/people-traveling-in-the-desert-1739011/)



[Play button svg **in white**](https://raw.githubusercontent.com/mau-jac/2W6-UI/master/docs/wk10/assets/play.svg?sanitize=true) to be placed on top of the video thumbnails.

**Hint 1**: Use the link above as the src of an <img> element. SVG images can shrink or grow indefinitely so do not forget to specify a width.

**Hint 2**: There are different ways to overlay an image on top of another image. I recommend using position absolute.



## Annex B: Layout Example

Consider that we would like to clone YouTube’s home page. Below is an image of the page with the viewport width between 870px and 1120px.



![img](https://lh4.googleusercontent.com/tn06KTy1sKmcx7fPPFb-QXWSSnKKHHFkPlrWc5mUd0GvVn0A3gR8Qb2bLbvYVK015oDPDFenGa3t36k-LiSkiNS86nASeUbS9SKENFsRRh5Hkhj1hx2CvxtFmsHAHeqinQusH2bs)





There are many possible ways to layout this site using **Grid and Flexbox**, what follows is one approach.

Starting with the overall site layout.



![img](https://docs.google.com/drawings/u/0/d/s8dfWYw_2a1q_Uc8zWw5g-w/image?w=672&h=575&rev=1&ac=1&parent=1PYS_r-FEFzrhmapXaG-kGCN9HdFv42ptVnStxKFljpc)





I would make most other sections of the website (such as the header and navbar) with either default block-level behaviour or Flexbox so they don’t need to be included.



Next section that will use grid is video suggestions section:



![img](https://docs.google.com/drawings/u/0/d/sK0lrPGNRBOvIq-OvhSwSKw/image?w=604&h=492&rev=72&ac=1&parent=1PYS_r-FEFzrhmapXaG-kGCN9HdFv42ptVnStxKFljpc)