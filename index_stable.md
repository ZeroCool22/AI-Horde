<html data-lt-installed="true"><head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <title>Stable Horde</title>
    <meta name="google-site-verification" content="pmLKyCEPKM5csKT9mW1ZbGLu2TX_wD0S5FCxWlmg_iI">
    <link rel="preconnect" href="https://fonts.googleapis.com/" crossorigin="true"><link rel="preconnect" href="https://fonts.gstatic.com/"><link rel="stylesheet" href="Stable%20Horde_archivos/css2.css">
    <link rel="stylesheet" href="style.css">
</head>
<!-- Added some open links in a new TAB and align 0.jpg to the left, so it match with the rest of the images alignment -->
    <body><h1>Stable Horde</h1>
<div><img style="text-align: left;" src="Stable%20Horde_archivos/0.jpg" width="300"> </div>
<p>This is a <a href="https://github.com/db0/Stable-Horde">crowdsourced distributed cluster</a> of <a href="https://github.com/db0/stable-diffusion-webui">Stable Diffusion workers</a>. If you like this service, consider joining the horde yourself!</p>
<p>Also check out our sister project for text generation: <a href="https://koboldai.net/">KoboldAI Horde</a></p>
<h2>📊Stats</h2>
<ul>
<li>Average Recent Performance: 7.7 megapixelsteps per second</li>
<li>Total GPS generated: 1.2 terapixelsteps</li>
<li>Total requests fulfilled: 84.1K</li>
<li>Active <a href="https://stablehorde.net/api/v2/workers">Workers</a>: 5</li>
<li>Queue: 8 requests for a total of 260.8 megapixelsteps</li>
</ul>
<h2>🔋Usage</h2>
<p>First <a href="https://stablehorde.net/register">Register an account</a> which will generate for you an API key. Store that key somewhere.</p>
<ul>
<li>if you do not want to register, you can use '0000000000' as api_key 
to connect anonymously. However anonymous accounts have the lowest 
priority when there's too many concurrent requests!</li>
<li>To increase your priority you will need a unique API key and then to increase your Kudos. <a href="https://dbzer0.com/blog/the-kudos-based-economy-for-the-koboldai-horde/">Read how Kudos are working</a>.</li>
</ul>
<h3>💻GUI</h3>
<p>We provide <a href="https://dbzer0.itch.io/stable-horde-client">a client interface</a> requiring no installation and no technical expertise</p>
<p><img src="Stable%20Horde_archivos/screenshot.png" width="500"></p>
<h3>🆑Command Line</h3>
<ol>
<li>Git clone <a href="https://github.com/db0/Stable-Horde">this repository</a></li>
<html data-lt-installed="true"><head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <title>Stable Horde</title>
    <meta name="google-site-verification" content="pmLKyCEPKM5csKT9mW1ZbGLu2TX_wD0S5FCxWlmg_iI">
    <link rel="preconnect" href="https://fonts.googleapis.com/" crossorigin="true"><link rel="preconnect" href="https://fonts.gstatic.com/"><link rel="stylesheet" href="Stable%20Horde_archivos/css2.css">
    <link rel="stylesheet" href="style.css">
</head>
<!-- Added some open links in a new TAB and align 0.jpg to the left, so it match with the rest of the images alignment -->
    <body><h1>Stable Horde</h1>
<div><img style="text-align: left;" src="Stable%20Horde_archivos/0.jpg" width="300"> </div>
<p>This is a <a href="https://github.com/db0/Stable-Horde">crowdsourced distributed cluster</a> of <a href="https://github.com/db0/stable-diffusion-webui">Stable Diffusion workers</a>. If you like this service, consider joining the horde yourself!</p>
<p>Also check out our sister project for text generation: <a href="https://koboldai.net/">KoboldAI Horde</a></p>
<h2>📊Stats</h2>
<ul>
<li>Average Recent Performance: 7.7 megapixelsteps per second</li>
<li>Total GPS generated: 1.2 terapixelsteps</li>
<li>Total requests fulfilled: 84.1K</li>
<li>Active <a href="https://stablehorde.net/api/v2/workers">Workers</a>: 5</li>
<li>Queue: 8 requests for a total of 260.8 megapixelsteps</li>
</ul>
<h2>🔋Usage</h2>
<p>First <a href="https://stablehorde.net/register">Register an account</a> which will generate for you an API key. Store that key somewhere.</p>
<ul>
<li>if you do not want to register, you can use '0000000000' as api_key 
to connect anonymously. However anonymous accounts have the lowest 
priority when there's too many concurrent requests!</li>
<li>To increase your priority you will need a unique API key and then to increase your Kudos. <a href="https://dbzer0.com/blog/the-kudos-based-economy-for-the-koboldai-horde/">Read how Kudos are working</a>.</li>
</ul>
<h3>💻GUI</h3>
<p>We provide <a href="https://dbzer0.itch.io/stable-horde-client">a client interface</a> requiring no installation and no technical expertise</p>
<p><img src="Stable%20Horde_archivos/screenshot.png" width="500"></p>
<h3>🆑Command Line</h3>
<ol>
<li>Git clone <a href="https://github.com/db0/Stable-Horde">this repository</a></li>
<li>Make sure you have python3 installed</li>
<li>Open a git bash (or just bash in linux)</li>
<li>Download the cli requirements with <code>python -m pip install -r cli_requirements.txt --user</code></li>
<li>Run <code>./cli_requests.py</code> </li>
</ol>
<p>You can use <code>./cli_requests.py -h</code> to see the command line arguments to use</p>
<p>You can make a copy of <code>cliRequestData_template.py</code> into <code>cliRequestData.py</code> and edit it, to use common variables for your generations. Command line arguments will always take precedence over <code>cliRequestData.py</code> so you can use them to tweak your generations slightly.</p>
<h3>🔩Tools</h3>
<p>We provide a <a href="https://github.com/db0/Stable-Horde-Client-Addon">Godot Engine plugin</a> to integrate Stable Horde image generation into your games.</p>
<h2>🔍REST API</h2>
<p><a href="https://stablehorde.net/api">Full Documentation</a></p>
<h2>💡Services</h2>
<ul>
<li><a href="https://stablehorde.net/register">Register New Account</a></li>
<li><a href="https://stablehorde.net/transfer">Transfer Kudos</a></li>
</ul>
<h2>💪Community</h2>
<ul>
<li>Join us on <a href="https://discord.gg/3DxrhksKzn">Discord</a></li>
<li>Support the development of the Stable Horde on <a href="https://www.patreon.com/db0">Patreon</a> or <a href="https://github.com/db0">Github</a></li>
</ul>
<h2>📋Credits</h2>
<p>These are the people who made this sotware possible.</p>
<ul>
<li><a href="https://dbzer0.com/">Db0</a> - Development and Maintenance</li>
</ul>
<p>And of course, everyone contributing their SD to the horde!</p>
<h2>💯Top Contributors</h2>
<p>These are the people and workers who have contributed most to this horde.</p>
<h3>🎭Users</h3>
<p>This is the person whose worker(s) have generated the most pixels for the horde.</p>
<h4>db0#1</h4>
<ul>
<li>568.0 gigapixelsteps generated.</li>
<li>39.3K requests fulfilled.</li>
</ul>
<h3>📟Workers</h3>
<p>This is the worker which has generated the most pixels for the horde.</p>
<h4>The Portal of Infinite Realities</h4>
<ul>
<li>606.4 gigapixelsteps generated.</li>
<li>42.2K request fulfillments.</li>
<li>13.97 days uptime.</li>
</ul>
<p><img src="Stable%20Horde_archivos/1.jpg" width="800"></p>
<h2>📌Policies</h2>
<p><a href="https://stablehorde.net/privacy">Privacy Policy</a></p>
<p><a href="https://stablehorde.net/terms">Terms of Service</a></p></body></html>
