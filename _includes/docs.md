{::options parse_block_html="true" /}

## Getting started
{:.title.text-center}

<div class="block">
### Install
{:.sub-title.text-center}

<pre><code class="language-bash">
    $ pip install tables

</code></pre>

</div>

<div class="block">
### Create a PyTables file
{:.sub-title.text-center}

Creating a PyTables file from scratch.

<pre><code class="language-python">
    import tables

    h5 = tables.open_file('detector.h5', mode = 'w', title = 'Test file')

</code></pre>

Crate a new group

<pre><code class="language-python">
    group = h5file.create_group("/", 'detector', 'Detector information')
</code></pre>

Do other amazing things!

</div>

<div class="block">
### I want more
{:.sub-title.text-center}

If your documentation is very long you can host the full docs page (including
FAQ etc) on GitHub and provide a Call to Action button below to direct users
there.

<a class="btn btn-cta-primary" href="https://github.com/twbs/bootstrap" target="_blank">Full documentation</a>
{:.text-center}

</div><!--//block-->


