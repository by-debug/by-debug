<h1 align="center">Hi 👋, I'm by-debug</h1>
<h3 align="center">A high school student from Taiwan</h3>

<style>
    :root
    {
        --dark-color: #0000ff;
        --light-color: #00ffff;
    }
    svg
    {
        cursor: pointer;
    }
    #dark_g
    {
        fill: var(--dark-color);
    }
    #light_g
    {
        fill: var(--light-color);
    }
    #dark2,
    #light1,
    #dark1
    {
        transition: all 1s ease;
    }
    #dark1
    {
        transform: translateX(-100%);
    }
    svg:hover #dark2
    {
        transform: translateX(40%);
        opacity: 0;
    }
    svg:hover #light1
    {
        transform: translateX(20%);
    }
    svg:hover #dark1
    {
        transform: translateX(0%);
    }
</style>
<svg
width="12mm"
height="10mm"
viewBox="0 0 120 100"
version="1.1"
id="svg5"
xmlns="http://www.w3.org/2000/svg"
xmlns:svg="http://www.w3.org/2000/svg">
<defs
    id="defs2" />
<g
    id="layer1">
    <g
    id="bys">
    <g
        id="light_g"
        transform="matrix(0.60841249,0,0,0.60841249,-25.224541,2.9559717)">
        <path
        id="light1"
        opacity="0.6"
        style="fill-rule:evenodd;stroke:none;stroke-width:0.177179;stroke-opacity:1"
        d="M 66.818874,6.2783821 V 88.599963 h 8.391221 v -31.31643 l 21.554757,16.4021 -42.325583,54.568757 6.634736,5.14594 42.373125,-54.630257 0.10438,0.0796 5.08083,-6.76445 -6.63474,-5.14594 -0.0475,0.061 -26.739965,-20.34708 V 6.2783821 Z" />
    </g>
    <g
        id="dark_g"
        transform="matrix(0.60841249,0,0,0.60841249,3.4147979,-48.368755)"
        style="stroke-width:1;stroke-miterlimit:4;stroke-dasharray:none">
        <path
        id="dark2"
        opacity="0.8"
        style="fill-rule:evenodd;stroke:none;stroke-width:1;stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
        d="m 41.320974,90.264434 v 82.321596 h 8.39122 v -31.31644 l 21.55476,16.4021 -42.32558,54.56877 6.63473,5.14594 42.37313,-54.63026 0.10438,0.0796 5.08083,-6.76445 -6.63474,-5.14594 -0.0475,0.061 -26.73997,-20.34712 V 90.264434 Z" />
        <path
        id="dark1"
        opacity="0.8"
        style="fill-rule:evenodd;stroke:none;stroke-width:1;stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:1"
        d="M 19.746626,90.636812 V 172.9584 h 8.391221 v -31.31644 l 21.55475,16.4021 -42.3255807,54.56876 6.6347397,5.14594 42.373121,-54.63025 0.10439,0.0796 5.08083,-6.76445 -6.63474,-5.14593 -0.0475,0.061 -26.73997,-20.34708 V 90.636862 Z" />
    </g>
    </g>
</g>
</svg>

<script>
const svg = document.getElementById("bys");

svg.onclick = (e) => {
    const colors = ['red','blue','green','orange','pink','purple'];
    const randco = colors[Math.floor(Math.random()*colors.length)];
    document.documentElement.style.cssText = `
    --dark-color: ${randco};
    --light-color: ${randco};
    `
}
</script>

<p align="left"> <a href="https://twitter.com/by_debug" target="blank"><img src="https://img.shields.io/twitter/follow/by_debug?logo=twitter&style=for-the-badge" alt="by_debug" /></a> </p>

- 🌱 I’m currently learning **c++, javascript & python**

- 📝 I regularly write articles on [https://by-debug.github.io/](https://by-debug.github.io/)

- 📫 How to reach me **quantumdebugger@duck.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/by_debug" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="by_debug" height="30" width="40" /></a>
<a href="https://stackoverflow.com/users/14922848" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="14922848" height="30" width="40" /></a>
<a href="https://codeforces.com/profile/by20051002" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codeforces.svg" alt="by20051002" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://gohugo.io/" target="_blank" rel="noreferrer"> <img src="https://api.iconify.design/logos-hugo.svg" alt="hugo" width="40" height="40"/> </a> <a href="https://ifttt.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/ifttt/ifttt-ar21.svg" alt="ifttt" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.selenium.dev" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="40" height="40"/> </a> <a href="https://www.sqlite.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=by-debug&show_icons=true&locale=en&layout=compact" alt="by-debug" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=by-debug&show_icons=true&locale=en" alt="by-debug" /></p>
