# Code 201 Reading Notes

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)
This is told naratively about Julia Rozovsky, a 26 yrar old working at getting a business degree from harvard. Her class teams made her uncomfortable because it was very competative/achievement/recognition/authority-based and she didn't enjoy that.
She found another team which was also working hard on the same types of topics but people were diverse in backgrounds, had more humor, creativity and seemed more colaberative and open than competitive and judgemental within the team (the teams competed with other teams)'

Article switches to high level philosophy about the modern human condition. Discusses the panopticon of modern work life with glowing warm  terms but says it isn't enough when applied to individuals it also needs to be done to our social groups and peofessional bonds. Talks of the scientific management method and of using statistics to reduce emotional connections to variables to increase output in fields that need innovation or creativity. It discusses darwinian economics of the modern markets of products and ideologies.

They discussed the use of conventual wisdow and turning the scientific method to examine human interaction and how best to harness an objective measure of company profit. This reminds me of : https://www.youtube.com/watch?v=oXAWMd-h96k

This was ironically code-named Project Aristotle. They had a hard time of finding patterns to the perfect team, but did come across group norms, sociology 101. Which the relationships varied widely and did not corrolate to productity, group norms did have observable and predictable effects.

Basically it is about fitting the right people into places where they fit the social norms because then groups functioning which is defined by those norms don't grind gears.

The best teams also have people whom are empathetic because that helps them adjust to others, and also helps everyone treat each other with respect, especially useful if everyone thinks 'respect' means the same thing.

> ‘‘It describes a team climate characterized by interpersonal trust and mutual respect in which people are comfortable being themselves.’’ ~ Edmondson wrote in a study published in 1999.

That is psychological safety.

They go back to naration for the bit where they study it in google with surveys and talk about good and bad cases of social norms.

I agree psychological safety and emotional conversations are related. not being fully present at work, where a "work mask" is a bummer

> "The paradox, of course, is that Google’s intense data collection and number crunching have led it to the same conclusions that good managers have always known. In the best teams, members listen to one another and show sensitivity to feelings and needs." the article

This article give credibility to feeling which they always should have had in my opinion

The thought "What group is right for me?" is my biggest take away.

The following reading is required for psychological safety talk on class 14:

[What Google Learned From Its Quest to Build the Perfect Team](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html)


Read the following articles and/or review the following examples on CSS animations:

### [Read this article on CSS Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

#### Transitions
* PsudoClasses = :hover, :focus, :active, and :target
* Transitions = transition-property, transition-duration, transition-timing-function, and transition-delay


* Example:

        HTML
        <div class="card-container">
        <div class="card">
            <div class="side">...</div>
            <div class="side back">...</div>
        </div>
        </div>

                        
        CSS
        .card-container {
        height: 150px;
        perspective: 600;
        position: relative;
        width: 150px;
        }
        .card {
        height: 100%;
        position: absolute;
        transform-style: preserve-3d;
        transition: all 1s ease-in-out;
        width: 100%;
        }
        .card:hover {
        transform: rotateY(180deg);
        }
        .card .side {
        backface-visibility: hidden;
        height: 100%;
        position: absolute;
        width: 100%;
        }
        .card .back {
        transform: rotateY(180deg);
        }


### [8 simple CSS3 transitions that will wow your users](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/)
1. fade in, just like it sounds
        .fade {
            opacity:0.5;
        }
        .fade:hover {
        opacity:1;
        }
2. Change color (via hover)
3. Shrink or grow, via hover controling these:
        .grow:hover {
            -webkit-transform: scale(1.3);
            -ms-transform: scale(1.3);
            transform: scale(1.3);
        }
4. Rotate elements, with rotate specific transformers
5. Square to circle
        .circle:hover {
        border-radius:50%;
        }
6.  3D shadow
7. Swing, side to side movement
8. Inset border


### [6 Buttons animated](https://codepen.io/retyui/pen/ByoaXV)
* The buttoms bob like they are floating over the page, usesthings like: ```-webkit-animation: pulse 1s linear infinite alternate;```
### [CSS3 Animations: Keyframes](https://codepen.io/akshaychauhan/pen/oAfae)
* 
### [404](https://codepen.io/kieranfivestars/pen/MYdQxX)
* Example what was done with three sibling h1 elements of 4 0 4, they cycle overlapping in an infinite 4 second loop
            ```body {
            margin:0;
            font-family:sans-serif;
            color:#f25252;
            background:#f7f7f7;
            }
            h1 {
            font-size:11rem;
            position:absolute;
            transform:translate(-50%,-50%);
            margin:0;
            }
            h1:nth-of-type(1){
            animation: range 4s infinite;
            }
            h1:nth-of-type(2){
            left:50%;
            top:50%;
            animation: size 4s infinite;
            }
            h1:nth-of-type(3){
            animation: range2 4s infinite;
            }
            @keyframes range {
            0%  {left:42%;top:50%;font-size:11rem;}
            25% {left:50%;top:40%;font-size:4.5rem;}
            50% {left:58%;top:50%;font-size:11rem;}
            75% {left:50%;top:60%;font-size:4.5rem;}
            100%{left:42%;top:50%;font-size:11rem;}
            }
            @keyframes range2 {
            0%  {left:58%;top:50%;font-size:11rem;}
            25% {left:50%;top:60%;font-size:4.5rem;}
            50% {left:42%;top:50%;font-size:11rem;}
            75% {left:50%;top:40%;font-size:4.5rem;}
            100%{left:58%;top:50%;font-size:11rem;}
            }
            @keyframes size {
            0%  {font-size:11rem;}
            25% {font-size:26rem;}
            50% {font-size:11rem;}
            75% {font-size:26rem;}
            100%{font-size:11rem;}
            }```



















[Pure CSS Bounce Animation]