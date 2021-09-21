<pre style="color: white; background: #22272E; border-radius: 8px; padding: 10px; box-shadow: 1px 1px 14px  4px rgba(49, 109, 202, 0.5);">
    <div style="display: flex;">
        <div style="background: #FF5F56; margin-right: 10px; width: 10px; height: 10px; border-radius: 50%;"></div>
        <div style="background: #FFBD2E; margin-right: 10px; width: 10px; height: 10px; border-radius: 50%;"></div>
        <div style="background: #27C93F; margin-right: 10px; width: 10px; height: 10px; border-radius: 50%;"></div>
    </div>
<span style="font-size: 14px; font-weight: bold;">>>> sujal --help</span> 
    <code>
    Sujal is a tool for developing HTML/CSS/JS/PYTHON,
    In case of missing skill dependencies, automatically tries to resolve.

    Usage:
        sujal [OPTIONS] ... &lt;command&gt; [ARGUMENTS] ...

    Options:
        -p, --python       develop with Python
        -m, --html         develop fronted with HTML
        -c, --css          style html with CSS
        -j, --javascript   develop with JavaScript
        -f                 develop fast
        -s                 write quality code
        -h, --help         echo this help and exit

    Commands:
        develop           make a project with specified language option and description argument
        maintain          toggles no-quit flag on project. When true, quit command raises errors
        quit              stop development for a project
        sleep             internally called by quit, explicit calls require time argument
    </code>
</pre>