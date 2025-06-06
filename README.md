 <!-- Content render By JAVASCRIPT -->
          <div class="page_header">
            <img
              src="./images/reactjslogo.png"
              alt="reactLogo"
              class="LangLogo"
            />
            <span>
              <h1 class="page_topic">Understanding Hooks</h1>
              <span class="name_credit"
                ><img
                  src="https://www.youtube.com/favicon.ico"
                  alt="credit"
                  class="credit"
                />
                <p>Taught By <b>Code with Deepanshu Knox</b></p></span
              >
            </span>
          </div>

          <h2 class="page_topic">React Hooks – Quick Guide</h2>

          <p class="page_paras">
            React Hooks allow functional components to access state and other
            React features without writing class components. Introduced in React
            16.8, Hooks simplify code and promote reusability.
          </p>

          <!-- <h2 class="sub_topics">What is a Hook?</h2> -->

          <p class="page_paras">
            A Hook is a special function that lets you "hook into" React
            features like state and lifecycle methods. Hooks can only be used
            inside functional components and must be called at the top level.
          </p>

          <h3 class="sub_topics" style="padding-top: 10px">
            Here is an Example :
          </h3>

          <p class="page_paras">
            Don't worry if it doesn't make sense. We will go into more detail in
            the <span class="hillight">next section</span>
          </p>

          <pre><code class="language-javascript" style="font-family: Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace;">import React, { useState } from "react";
import ReactDOM from "react-dom/client";

function FavoriteColor() {
  const [color, setColor] = useState("red");

  return (
    &lt;&gt;
      &lt;h1&gt;My favorite color is {color}!&lt;/h1&gt;
      &lt;button type="button" onClick={() => setColor("blue")}&gt; Blue &lt;/button&gt;
    &lt;/&gt;
  );
}

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(&lt;FavoriteColor /&gt;);
</code></pre>

          <p class="page_paras">
            - Here we are using the useState Hook to keep track of the
            application state.
          </p>
          <p class="page_paras">- You must import Hooks from react.</p>

          <p class="page_paras">
            - State generally refers to application data or properties that need
            to be tracked.
          </p>
