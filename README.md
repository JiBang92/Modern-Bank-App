<h1>Hoobank - Modern Bank App</h1>
<p><i>Tutorial Provided By: <a href="https://www.youtube.com/watch?v=F627pKNUCVQ&list=PL6QREj8te1P6CkO_4OIK1-nwG5OxCD5tR&index=8&ab_channel=JavaScriptMastery">JavaScript Mastery</a></i></p>

<br/>
*
<br/>
*
<br/>
*
<br/>
<br/>

<h2><b>About</b></h2>
<p>This app features only one dependency - Tailwind CSS - and its versatility.</p>

> <b><i>NOTE:</b> This application is UI/UX focused and does not demonstrate full website functionality.</i>

<br/>

|                   <b>FEATURES</b>                   |                                                   <b>DESCRIPTIONS</b>                                                   |
| :-------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------: |
| <a href="https://tailwindcss.com/">Tailwind CSS</a> | A utility-first CSS framework packed with classes ... that can be composed to build any design, directly in your markup |

<br/>
*
<br/>
*
<br/>
*
<br/>
<br/>

<h3><b>Example of Tailwind CSS Usage</b></h3>

```js
<ul className="list-none sm:flex hidden justify-end items-center flex-1">
  {navLinks.map((nav, index) => (
    <li
      key={nav.id}
      className={`font-poppins font-normal cursor-pointer text-[16px] ${
        index === navLinks.length - 1 ? "mr-0" : "mr-10"
      } text-white`}
    >
      <a href={`#${nav.id}`}>{nav.title}</a>
    </li>
  ))}
</ul>
```

<br/>

|   <b>Property</b>   |       <b>Equivalent</b>       |                                 <b>Learn More</b>                                  |
| :-----------------: | :---------------------------: | :--------------------------------------------------------------------------------: |
|  <b>list-none</b>   |     list-style-type: none     |     <a href="https://tailwindcss.com/docs/list-style-type">List Style Type</a>     |
|   <b>sm:flex</b>    | Breakpoints and Media Queries | <a href="https://tailwindcss.com/docs/flex#breakpoints-and-media-queries">Flex</a> |
|    <b>hidden</b>    |         display: none         |         <a href="https://tailwindcss.com/docs/display#hidden">Display</a>          |
| <b>justify-end</b>  |   justify-content: flex-end   |   <a href="https://tailwindcss.com/docs/justify-content#end">Justify Content</a>   |
| <b>items-center</b> |      align-items: center      |     <a href="https://tailwindcss.com/docs/align-items#center">Align Items</a>      |
|    <b>flex-1</b>    |         flex: 1 1 0%          |            <a href="https://tailwindcss.com/docs/display#flex">Flex</a>            |

<br/>

<p>This renders the navigation links on the right-hand side.</p>

<img src="./public/hoobank-nav-links.png" alt="Hoobank Navigation Links"/>

<br/>

<p>And there you have it! This entire application is created with very minimal CSS and mostly with Tailwind.</p>
