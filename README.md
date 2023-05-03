# playerscommittee.org

* Each page is a [markdown](https://www.markdownguide.org/cheat-sheet/) file.
* To add a new page, create a markdown file. For example: `my-new-page.md`
* At the top of the file is [Jekyll Frontmatter](https://jekyllrb.com/docs/front-matter/). For example:
  ```yaml
  ---
  layout: default
  title: My New Page
  permalink: /my-new-page/
  ---
  ```
* Each page includes a theme layout. For example: `layout: default` would use the **default** layout. The layout files are stored in `_layouts`. The **default** layout file would be: `_layouts/default.html`
* The **default** layout includes a navigation header bar at the top of the page:
  ```html
      <div id="header">
        <nav>
          <ul>
            <li style="float: left; margin-left: 0px;"><a href="/" style="background:none; padding:0px; border:none;"><img src="/assets/images/swccgpc_wb.svg" onmouseover="this.src='/assets/images/swccgpc_bw.svg'" onmouseout="this.src='/assets/images/swccgpc_wb.svg'" style="height:50px;" /></a></li>
            <li class="fork">&nbsp;</li>
            <li class="fork"><a href="/about">About</a></li>
            <li class="fork"><a href="/swccg">SWCCG</a></li>
            <li class="fork"><a href="/young-jedi">Young Jedi</a></li>
            <li class="fork"><a href="/jedi-knights">Jedi Knights</a></li>
            <li class="downloads"><a href="/donate">Donate</a></li>
          </ul>
        </nav>
      </div><!-- end header -->
  ```
* CSS Colors can be modified in `_sass/jekyll-theme-midnight.scss`

