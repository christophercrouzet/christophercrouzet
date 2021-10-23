# Hi, I’m Christopher! :wave:

Originally from France :fr:, I was a technical artist for over 8 years on VFX and animation movies, but I've since then transitioned to being a full-time software engineer who strives in designing and building tools, workflows, and APIs, with a focus not only on user experience and simplicity, but also on maintainability.

As the time goes by, I'm increasingly being drawn towards lower level territory and have a strong interest in real-time, graphics, simulation, compiler, and also performance programming, for all of which I'm yearning to grow my skills in.

Most of the projects listed in this page were developed as the result of wanting to explore and learn specific topics.

I don't bite so come say hi! :blush:


## Projects in C/C++ :rocket:

<dl>
    <dt>rexo</dt>
    <dd>
        Single-file cross-platform unit testing framework with automatic test registration and an emphasis on providing a clean API.
        <ul>
            <li><a href="https://github.com/christophercrouzet/rexo">repository</a></li>
            <li><a href="https://christophercrouzet.github.io/rexo">documentation</a></li>
            <li><a href="https://christophercrouzet.com/blog/dev/rexo-part-2">blog post</a></li>
        </ul>
    </dd>
    <dt>uuki</dt>
    <dd>
        Toy project to learn about writing compilers—I haven't really started working on it other than writing a base library with no dependency towards the CRT, no dynamic allocations, some debugging utilities, a colorful logger, a virtual memory API, a custom linear allocator, and a growable array.
        <ul>
            <li><a href="https://github.com/christophercrouzet/uuki">repository</a></li>
        </ul>
    </dd>
    <dt>zero</dt>
    <dd>
        Experiment in writing single-file libraries with no <code>#include</code> statements in the header sections, as described in the article <a href="http://ourmachinery.com/post/physical-design">Physical Design of The Machinery</a>.
        <ul>
            <li><a href="https://github.com/christophercrouzet/zero">repository</a></li>
            <li><a href="https://christophercrouzet.com/blog/dev/zero">blog post</a></li>
        </ul>
    </dd>
    <dt>dekoi</dt>
    <dd>
        Playground to learn about the Vulkan API by following the <a href="https://vulkan-tutorial.com">Vulkan Tutorial</a> and adapting it to C.
        <ul>
            <li><a href="https://github.com/christophercrouzet/dekoi">repository</a></li>
        </ul>
    </dd>
    <dt>m3ta</dt>
    <dd>
        Header-only library to experiment with how much code can be evaluated at compile-time using C++'s templates. The answer is: a lot! C++ templates are in fact turing complete! :smile:
        <ul>
            <li><a href="https://github.com/christophercrouzet/m3ta">repository</a></li>
            <li><a href="https://m3ta.readthedocs.io/">documentation</a></li>
            <li><a href="https://christophercrouzet.com/blog/dev/m3ta">blog post</a></li>
        </ul>
    </dd>
</dl>


## Projects in Python :snake:

<dl>
    <dt>hienoi</dt>
    <dd>
        Framework to simulate 2D particles. It was a good exercise to learn about OpenGL, NumPy, IPC (Inter-Process Communication), and to figure out how to abstract all this through an easy-to-use API.
        <ul>
            <li><a href="https://github.com/christophercrouzet/hienoi">repository</a></li>
            <li><a href="https://christophercrouzet.com/blog/dev/hienoi">blog post</a></li>
        </ul>
    </dd>
    <dt>wadu</dt>
    <dd>
        Implementation of recurrence rules for calendar events as defined in the <a href="https://tools.ietf.org/html/rfc5545#section-3.3.10">RFC 5545 specification</a>. I expected it to be challenging and it really didn't disappoint! :sweat_smile: 
        <ul>
            <li><a href="https://github.com/christophercrouzet/wadu">repository</a></li>
            <li><a href="https://christophercrouzet.com/blog/dev/wadu">blog post</a></li>
        </ul>
    </dd>
    <dt>gorilla</dt>
    <dd>
        Framework that provides a convenient approach to monkey patching. Mostly done to build experience in designing APIs and delivering a fully finished project, with unit tests and documentation.
        <ul>
            <li><a href="https://github.com/christophercrouzet/gorilla">repository</a></li>
            <li><a href="https://gorilla.readthedocs.io">documentation</a></li>
            <li><a href="https://christophercrouzet.com/blog/dev/gorilla-and-bananas">blog post</a></li>
        </ul>
    </dd>
    <dt>bana</dt>
    <dd>
        Tiny set of extention for the Maya Python API built on top of Gorilla, as a way to validate the design of Gorilla.
        <ul>
            <li><a href="https://github.com/christophercrouzet/bana">repository</a></li>
            <li><a href="https://bana.readthedocs.io">documentation</a></li>
            <li><a href="https://christophercrouzet.com/blog/dev/gorilla-and-bananas">blog post</a></li>
        </ul>
    </dd>
    <dt>revl</dt>
    <dd>
        Library to generate pseudo-random (deterministic) Maya scenes based on a set of rules, in order to provide something akin to fuzzy testing and also to help profiling performance.
        <ul>
            <li><a href="https://github.com/christophercrouzet/revl">repository</a></li>
            <li><a href="https://revl.readthedocs.io">documentation</a></li>
        </ul>
    </dd>
</dl>


## Projects in JavaScript :globe_with_meridians: 

<dl>
    <dt>eddi</dt>
    <dd>
        Static site generator that is powering my current website. This was an interesting challenge to learn about Node.js and writing asynchronous code.
        <ul>
            <li><a href="https://github.com/christophercrouzet/eddi">repository</a></li>
        </ul>
    </dd>
</dl>
