This is where I will begin my website

  - October 26 - Began making website to showcase projects

    - Used Hugo extended to create the website using gokarna theme

    - Added _defaults folder to layouts, created list.html inside layout, created baseof.html inside _defaults,
    created single.html and added to _defaults, added sass folder to assets, added main.scss to sass

  - October 31
    - Cannot access the site anymore this is the error I got:

    ```
    WARN found no layout file for "html" for kind "page": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
    ```
    Still searching for a fix
    UPDATE:
    The fix was to run the commands ```git submodules init``` submodule and ```git update submodules``` submodule in the webiste folder. This error occured because I have 2 pc's. I mainly work from my desktop but because at this time I work from my laptop I not only needed to clone the repo but also update the git modules.
    answer: https://stackoverflow.com/questions/60269683/how-to-fix-the-error-found-no-layout-file-for-html-for-page-in-hugo-cms

    - Created 2 menu items that direct them to another page. These two pages are Arduino Uno R3 and About.

    - Partially filled section "Why create a website" in the About page.
