<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CV for rsschool</title>
        <link rel="stylesheet" href="style.css" >
        <link rel="icon" href="assets/favicon.ico">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link
            href="https://fonts.googleapis.com/css2?family=Spline+Sans:wght@300;400;500;600;700&display=swap"
            rel="stylesheet">
     
    </head>
    <body>
        <div class="main-block">
            <header>
                <nav>
                    <a  href="#skills"> Skills</a>
                   <a href="#code">Code examples</a>
                   <a href="#exp">Experience</a>
                   <a href="#DM">Why DataMola course?</a>
                   <a href="#edu">Education</a>
                   <a href="#lan">Languages</a>
                </nav>
                
            </header>
            <main>
                <hr>
                <div class="container">
                    
                    <div class="section">               
                        <div>
                            <img class="photo" src="assets/photo.jpg" alt="photo">       
                        </div>
                        <div class="contacts">
                            <h1>Marmysh Darya</h1>
                            <div style="display:flex; gap:20px">

                                <div>
                                    <p >github:</p>
                                    <p >email:</p>
                                    <p >vk: </p>
                                    <p>telegram: </p>
                                </div>
                                <div>
                                    <p><a href="https://github.com/DaryaMarmysh"><span class="ital">DaryaMarmysh</span></a></p>
                                        <p><span class="ital">vkmarmysh-darja@rambler.ru</span></p>
                                        <p><span class="ital">@ddd_mmm</span></p>
                                        <p><span class="ital">@daryamarmysh</span></p>
                                </div>
                            </div>

                          
                            <div class="about">
                                <h4>About me</h4> 
                                Student,
                                currently studying web
                                development and
                                everything related to it.<br> During my studies I
                                did
                                two
                                big projects.</div>
                        </div>
                        
                    </div>
                 
                   
                    <div id="skills" class="skills">
                        <h2>Skills</h2>
                        <ul>
                            <li>basic knowledge of HTML</li>
                            <li>basic knowledge of CSS (framework Tailwind CSS)</li>
                            <li>basic knowledge of JS</li>
                            <li>basic knowledge of C#</li>
                            <li>basic knowledge of sql</li>
                            <li>Figma</li>
                            <li>CorelDRAW</li>
                        </ul>
                    </div>
                    <div><h2 id="code">Code example</h2></div>
                    <div class="code-example">

                        <pre>
function list(names){
    var str='';
    for(var i=0;i&lt;names.length;i++)
    {
        str+=names[i].name;
        if((i+1)==names.length)
        {
            str+='';
        }
        else if((i+2)==names.length)
        {
            str+=' & ';
        }
        else
        {
            str+=', ';
        }
    }
    return(str) ;
}
</pre>
                    </div>
                </div>
                <div id="DM">
                    <h2>Why I'm interested in this course</h2>
                   <p> I want to get knowledge beyond the university curriculum and start working on real projects as soon as possible.
                </p>
                <br>
                    <p><span class="ital">P.S. This page was originally created for the "JS/FE Pre-School 2022" course from RSSCHOOL. </span></p>
                </div>
                <div id="exp" class="experience">
                    <h2>Experience</h2>
                    course work: <a href="https://github.com/DaryaMarmysh/WPF_project">&nbsp;Survey application on
                    WPF</a><br>
                    course work: <a href="https://github.com/DaryaMarmysh/botanic_garden_website">&nbsp;Site for a botanical
                    garden</a>
                   
                </div>
                <div id="edu" class="education">
                    <h2>Education</h2>
                    Belarusian State Technological University:

                    second year student of the Faculty of Information Technology
                </div>
                <div id="lan" class="languages">
                    <h2>Languages</h2>
                    <ul>
                    <li>Russian</li> 
                        <li>English (Pre-intermediate)</li>     
                </ul>
                </div>

            </main>
        </div>
        
        <footer>
            <div><a href="https://github.com/DaryaMarmysh">
                    <svg fill="#000000"
                            xmlns="http://www.w3.org/2000/svg" viewBox="0 0
                            30 30" width="60px" height="120px"> <path
                                d="M15,3C8.373,3,3,8.373,3,15c0,5.623,3.872,10.328,9.092,11.63C12.036,26.468,12,26.28,12,26.047v-2.051
                                c-0.487,0-1.303,0-1.508,0c-0.821,0-1.551-0.353-1.905-1.009c-0.393-0.729-0.461-1.844-1.435-2.526
                                c-0.289-0.227-0.069-0.486,0.264-0.451c0.615,0.174,1.125,0.596,1.605,1.222c0.478,0.627,0.703,0.769,1.596,0.769
                                c0.433,0,1.081-0.025,1.691-0.121c0.328-0.833,0.895-1.6,1.588-1.962c-3.996-0.411-5.903-2.399-5.903-5.098
                                c0-1.162,0.495-2.286,1.336-3.233C9.053,10.647,8.706,8.73,9.435,8c1.798,0,2.885,1.166,3.146,1.481C13.477,9.174,14.461,9,15.495,9
                                c1.036,0,2.024,0.174,2.922,0.483C18.675,9.17,19.763,8,21.565,8c0.732,0.731,0.381,2.656,0.102,3.594
                                c0.836,0.945,1.328,2.066,1.328,3.226c0,2.697-1.904,4.684-5.894,5.097C18.199,20.49,19,22.1,19,23.313v2.734
                                c0,0.104-0.023,0.179-0.035,0.268C23.641,24.676,27,20.236,27,15C27,8.373,21.627,3,15,3z"
                                /></svg></a></div>
                    <div>January 3rd, 2022</div>
                    <div style="width: 100px;"><a href="https://rs.school/js/">
                            <svg id="Layer_1"
                                xmlns="http://www.w3.org/2000/svg"
                                xmlns:xlink="http://www.w3.org/1999/xlink"
                                viewBox="0 0 600 205.3"><style>.st0{fill:#fff}.st1{clip-path:url(#SVGID_2_)}.st2{clip-path:url(#SVGID_4_)}.st3{clip-path:url(#SVGID_6_)}.st4{clip-path:url(#SVGID_8_)}.st5{fill:#fff;stroke:#000;stroke-width:4;stroke-miterlimit:10}.st6{clip-path:url(#SVGID_8_)}.st6,.st7{fill:none;stroke:#000;stroke-width:4;stroke-miterlimit:10}.st8,.st9{clip-path:url(#SVGID_10_)}.st9{fill:none;stroke:#000;stroke-width:4;stroke-miterlimit:10}</style><title>rs_school_js</title><path
                                    d="M285.4 68l26.3-1.7c.6 4.3 1.7 7.5 3.5
                                    9.8 2.9 3.6 6.9 5.4 12.2 5.4 3.9 0 7-.9
                                    9.1-2.8 2-1.5 3.2-3.9 3.2-6.4
                                    0-2.4-1.1-4.7-3-6.2-2-1.8-6.7-3.6-14.1-5.2-12.1-2.7-20.8-6.3-25.9-10.9-5.1-4.3-8-10.6-7.8-17.3
                                    0-4.6 1.4-9.2 4-13 3-4.3 7.1-7.7 12-9.6
                                    5.3-2.3 12.7-3.5 22-3.5 11.4 0 20.1 2.1
                                    26.1 6.4 6 4.2 9.6 11 10.7 20.3l-26
                                    1.5c-.7-4-2.1-6.9-4.4-8.8s-5.3-2.8-9.2-2.8c-3.2
                                    0-5.6.7-7.2 2-1.5 1.2-2.5 3-2.4 5 0
                                    1.5.8 2.9 2 3.8 1.3 1.2 4.4 2.3 9.3 3.3
                                    12.1 2.6 20.7 5.2 26 7.9 5.3 2.7 9.1 6
                                    11.4 9.9 2.4 4 3.6 8.6 3.5 13.3 0
                                    5.6-1.6 11.2-4.8 15.9-3.3 4.9-7.9
                                    8.7-13.3 11-5.7 2.5-12.9 3.8-21.5
                                    3.8-15.2 0-25.7-2.9-31.6-8.8S286.1 77
                                    285.4 68zM6.3 97.6V8.2h46.1c8.5 0 15.1.7
                                    19.6 2.2 4.4 1.4 8.3 4.3 10.9 8.2 2.9
                                    4.3 4.3 9.3 4.2 14.5.3 8.8-4.2 17.2-11.9
                                    21.6-3 1.7-6.3 2.9-9.7 3.5 2.5.7 5 1.9
                                    7.2 3.3 1.7 1.4 3.1 3 4.4 4.7 1.5 1.7
                                    2.8 3.6 3.9 5.6l13.4 25.9H63L48.2
                                    70.2c-1.9-3.5-3.5-5.8-5-6.9-2-1.4-4.4-2.1-6.8-2.1H34v36.3H6.3zM34
                                    44.4h11.7c2.5-.2 4.9-.6 7.3-1.2 1.8-.3
                                    3.4-1.3 4.5-2.8 2.7-3.6
                                    2.3-8.7-1-11.8-1.8-1.5-5.3-2.3-10.3-2.3H34v18.1zM0
                                    174.2l26.3-1.7c.6 4.3 1.7 7.5 3.5 9.8
                                    2.8 3.6 6.9 5.5 12.2 5.5 3.9 0 7-.9
                                    9.1-2.8 2-1.6 3.2-3.9 3.2-6.4
                                    0-2.4-1.1-4.7-3-6.2-2-1.8-6.7-3.6-14.2-5.2-12.1-2.7-20.8-6.3-25.9-10.9-5.1-4.3-8-10.6-7.8-17.3
                                    0-4.6 1.4-9.2 4-13 3-4.3 7.1-7.7 12-9.6
                                    5.3-2.3 12.7-3.5 22-3.5 11.4 0 20.1 2.1
                                    26.1 6.4s9.5 11 10.6 20.3l-26
                                    1.5c-.7-4-2.1-6.9-4.4-8.8-2.2-1.9-5.3-2.8-9.2-2.7-3.2
                                    0-5.6.7-7.2 2.1-1.6 1.2-2.5 3-2.4 5 0
                                    1.5.8 2.9 2 3.8 1.3 1.2 4.4 2.3 9.3 3.3
                                    12.1 2.6 20.7 5.2 26 7.9 5.3 2.7 9.1 6
                                    11.4 9.9 2.4 4 3.6 8.6 3.6 13.2 0
                                    5.6-1.7 11.1-4.8 15.8-3.3 4.9-7.9
                                    8.7-13.3 11-5.7 2.5-12.9 3.8-21.5
                                    3.8-15.2
                                    0-25.7-2.9-31.6-8.8-5.9-6-9.2-13.4-10-22.4z"
                                    /><path d="M133 167.2l24.2 7.3c-1.3
                                        6.1-4 11.9-7.7 17-3.4 4.5-7.9 8-13
                                        10.3-5.2 2.3-11.8 3.5-19.8 3.5-9.7
                                        0-17.7-1.4-23.8-4.2-6.2-2.8-11.5-7.8-16-14.9-4.5-7.1-6.7-16.2-6.7-27.3
                                        0-14.8 3.9-26.2 11.8-34.1s19-11.9
                                        33.4-11.9c11.3 0 20.1 2.3 26.6 6.8
                                        6.4 4.6 11.2 11.6 14.4 21l-24.4
                                        5.4c-.6-2.1-1.5-4.2-2.7-6-1.5-2.1-3.4-3.7-5.7-4.9-2.3-1.2-4.9-1.7-7.5-1.7-6.3
                                        0-11.1 2.5-14.4 7.6-2.5 3.7-3.8
                                        9.6-3.8 17.6 0 9.9 1.5 16.7 4.5 20.4
                                        3 3.7 7.2 5.5 12.7 5.5 5.3 0 9.3-1.5
                                        12-4.4 2.7-3.1 4.7-7.4
                                        5.9-13zm56.5-52.8h27.6v31.3h30.2v-31.3h27.8v89.4h-27.8v-36.2h-30.2v36.2h-27.6v-89.4z"
                                        /><path d="M271.3 159.1c0-14.6
                                            4.1-26 12.2-34.1 8.1-8.1
                                            19.5-12.2 34-12.2 14.9 0 26.3 4
                                            34.4 12S364 144 364 158.4c0
                                            10.5-1.8 19-5.3 25.7-3.4 6.6-8.7
                                            12-15.2 15.6-6.7 3.7-15 5.6-24.9
                                            5.6-10.1
                                            0-18.4-1.6-25-4.8-6.8-3.4-12.4-8.7-16.1-15.2-4.1-7-6.2-15.7-6.2-26.2zm27.6.1c0
                                            9 1.7 15.5 5 19.5 3.3 3.9 7.9
                                            5.9 13.7 5.9 5.9 0 10.5-1.9
                                            13.8-5.8s4.9-10.8
                                            4.9-20.8c0-8.4-1.7-14.6-5.1-18.4-3.4-3.9-8-5.8-13.8-5.8-5.1-.2-10
                                            2-13.4 5.9-3.4 3.9-5.1 10.4-5.1
                                            19.5zm93.4-.1c0-14.6 4.1-26
                                            12.2-34.1 8.1-8.1 19.5-12.2
                                            34-12.2 14.9 0 26.4 4 34.4
                                            12S485 144 485 158.4c0 10.5-1.8
                                            19-5.3 25.7-3.4 6.6-8.7 12-15.2
                                            15.6-6.7 3.7-15 5.6-24.9
                                            5.6-10.1
                                            0-18.4-1.6-25-4.8-6.8-3.4-12.4-8.7-16.1-15.2-4.1-7-6.2-15.7-6.2-26.2zm27.6.1c0
                                            9 1.7 15.5 5 19.5 3.3 3.9 7.9
                                            5.9 13.7 5.9 5.9 0 10.5-1.9
                                            13.8-5.8 3.3-3.9 4.9-10.8
                                            4.9-20.8
                                            0-8.4-1.7-14.6-5.1-18.4-3.4-3.9-8-5.8-13.8-5.8-5.1-.2-10.1
                                            2-13.4 5.9-3.4 3.9-5.1 10.4-5.1
                                            19.5z" /><path d="M482.1
                                                114.4h27.6v67.4h43.1v22H482v-89.4z"
                                                /><ellipse
                                                    transform="rotate(-37.001
                                                    420.46 67.88)"
                                                    class="st0" cx="420.5"
                                                    cy="67.9" rx="63"
                                                    ry="51.8" /><defs><ellipse
                                                            id="SVGID_1_"
                                                            transform="rotate(-37.001
                                                            420.46 67.88)"
                                                            cx="420.5"
                                                            cy="67.9"
                                                            rx="63"
                                                            ry="51.8" /></defs><clipPath
                                                            id="SVGID_2_"><use
                                                                xlink:href="#SVGID_1_"
                                                                overflow="visible"
                                                                /></clipPath><g
                                                                class="st1"><path
                                                                    transform="rotate(-37.001
                                                                    420.82
                                                                    68.353)"
                                                                    class="st0"
                                                                    d="M330.9-14.2h179.8v165.1H330.9z"
                                                                    /><g
                                                                        id="Layer_2_1_"><defs><path
                                                                                id="SVGID_3_"
                                                                                transform="rotate(-37.001
                                                                                420.82
                                                                                68.353)"
                                                                                d="M330.9-14.2h179.8v165.1H330.9z"
                                                                                /></defs><clipPath
                                                                                id="SVGID_4_"><use
                                                                                    xlink:href="#SVGID_3_"
                                                                                    overflow="visible"
                                                                                    /></clipPath><g
                                                                                    id="Layer_1-2"
                                                                                    class="st2"><ellipse
                                                                                        transform="rotate(-37.001
                                                                                        420.46
                                                                                        67.88)"
                                                                                        class="st0"
                                                                                        cx="420.5"
                                                                                        cy="67.9"
                                                                                        rx="63"
                                                                                        ry="51.8"
                                                                                        /><defs><ellipse
                                                                                                id="SVGID_5_"
                                                                                                transform="rotate(-37.001
                                                                                                420.46
                                                                                                67.88)"
                                                                                                cx="420.5"
                                                                                                cy="67.9"
                                                                                                rx="63"
                                                                                                ry="51.8"
                                                                                                /></defs><clipPath
                                                                                                id="SVGID_6_"><use
                                                                                                    xlink:href="#SVGID_5_"
                                                                                                    overflow="visible"
                                                                                                    /></clipPath><g
                                                                                                    class="st3"><path
                                                                                                        transform="rotate(-37
                                                                                                        420.799
                                                                                                        68.802)"
                                                                                                        class="st0"
                                                                                                        d="M357.8
                                                                                                        17h125.9v103.7H357.8z"
                                                                                                        /><defs><path
                                                                                                                id="SVGID_7_"
                                                                                                                transform="rotate(-37
                                                                                                                420.799
                                                                                                                68.802)"
                                                                                                                d="M357.8
                                                                                                                17h125.9v103.7H357.8z"
                                                                                                                /></defs><clipPath
                                                                                                                id="SVGID_8_"><use
                                                                                                                    xlink:href="#SVGID_7_"
                                                                                                                    overflow="visible"
                                                                                                                    /></clipPath><g
                                                                                                                    class="st4"><ellipse
                                                                                                                        transform="rotate(-37.001
                                                                                                                        420.46
                                                                                                                        67.88)"
                                                                                                                        class="st5"
                                                                                                                        cx="420.5"
                                                                                                                        cy="67.9"
                                                                                                                        rx="63"
                                                                                                                        ry="51.8"
                                                                                                                        /></g><path
                                                                                                                        transform="rotate(-37
                                                                                                                        420.799
                                                                                                                        68.802)"
                                                                                                                        class="st6"
                                                                                                                        d="M357.8
                                                                                                                        17h125.9v103.7H357.8z"
                                                                                                                        /><ellipse
                                                                                                                            transform="rotate(-37.001
                                                                                                                            420.46
                                                                                                                            67.88)"
                                                                                                                            class="st7"
                                                                                                                            cx="420.5"
                                                                                                                            cy="67.9"
                                                                                                                            rx="63"
                                                                                                                            ry="51.8"
                                                                                                                            /><path
                                                                                                                                transform="rotate(-37
                                                                                                                                420.799
                                                                                                                                68.802)"
                                                                                                                                class="st0"
                                                                                                                                d="M357.8
                                                                                                                                17h125.9v103.7H357.8z"
                                                                                                                                /><defs><path
                                                                                                                                        id="SVGID_9_"
                                                                                                                                        transform="rotate(-37
                                                                                                                                        420.799
                                                                                                                                        68.802)"
                                                                                                                                        d="M357.8
                                                                                                                                        17h125.9v103.7H357.8z"
                                                                                                                                        /></defs><clipPath
                                                                                                                                        id="SVGID_10_"><use
                                                                                                                                            xlink:href="#SVGID_9_"
                                                                                                                                            overflow="visible"
                                                                                                                                            /></clipPath><g
                                                                                                                                            class="st8"><ellipse
                                                                                                                                                transform="rotate(-37.001
                                                                                                                                                420.46
                                                                                                                                                67.88)"
                                                                                                                                                class="st5"
                                                                                                                                                cx="420.5"
                                                                                                                                                cy="67.9"
                                                                                                                                                rx="63"
                                                                                                                                                ry="51.8"
                                                                                                                                                /></g><path
                                                                                                                                                transform="rotate(-37
                                                                                                                                                420.799
                                                                                                                                                68.802)"
                                                                                                                                                class="st9"
                                                                                                                                                d="M357.8
                                                                                                                                                17h125.9v103.7H357.8z"
                                                                                                                                                /><path
                                                                                                                                                    transform="rotate(-37.001
                                                                                                                                                    420.82
                                                                                                                                                    68.353)"
                                                                                                                                                    class="st7"
                                                                                                                                                    d="M330.9-14.2h179.8v165.1H330.9z"
                                                                                                                                                    /></g><ellipse
                                                                                                                                                    transform="rotate(-37.001
                                                                                                                                                    420.46
                                                                                                                                                    67.88)"
                                                                                                                                                    class="st7"
                                                                                                                                                    cx="420.5"
                                                                                                                                                    cy="67.9"
                                                                                                                                                    rx="63"
                                                                                                                                                    ry="51.8"
                                                                                                                                                    /><path
                                                                                                                                                        d="M392.4
                                                                                                                                                        61.3l10-7
                                                                                                                                                        12.3
                                                                                                                                                        17.5c2.1
                                                                                                                                                        2.8
                                                                                                                                                        3.7
                                                                                                                                                        5.8
                                                                                                                                                        4.9
                                                                                                                                                        9.1.7
                                                                                                                                                        2.5.5
                                                                                                                                                        5.2-.5
                                                                                                                                                        7.6-1.3
                                                                                                                                                        3-3.4
                                                                                                                                                        5.5-6.2
                                                                                                                                                        7.3-3.3
                                                                                                                                                        2.3-6.1
                                                                                                                                                        3.6-8.5
                                                                                                                                                        4-2.3.4-4.7
                                                                                                                                                        0-6.9-1-2.4-1.2-4.5-2.9-6.1-5.1l8.6-8c.7
                                                                                                                                                        1.1
                                                                                                                                                        1.6
                                                                                                                                                        2.1
                                                                                                                                                        2.6
                                                                                                                                                        2.9.7.5
                                                                                                                                                        1.5.8
                                                                                                                                                        2.4.8.7
                                                                                                                                                        0
                                                                                                                                                        1.4-.3
                                                                                                                                                        1.9-.7
                                                                                                                                                        1-.6
                                                                                                                                                        1.7-1.8
                                                                                                                                                        1.6-3-.3-1.7-1-3.4-2.1-4.7l-14-19.7zm30
                                                                                                                                                        11.1l9.1-7.2c1
                                                                                                                                                        1.2
                                                                                                                                                        2.3
                                                                                                                                                        2.1
                                                                                                                                                        3.7
                                                                                                                                                        2.6
                                                                                                                                                        2
                                                                                                                                                        .6
                                                                                                                                                        4.1.2
                                                                                                                                                        5.8-1.1
                                                                                                                                                        1.2-.8
                                                                                                                                                        2.2-1.9
                                                                                                                                                        2.6-3.3.6-1.8-.4-3.8-2.2-4.4-.3-.1-.6-.2-.9-.2-1.2-.1-3.3.4-6.4
                                                                                                                                                        1.7-5.1
                                                                                                                                                        2.1-9.1
                                                                                                                                                        2.9-12.1
                                                                                                                                                        2.6-2.9-.3-5.6-1.8-7.2-4.3-1.2-1.7-1.8-3.7-1.9-5.7
                                                                                                                                                        0-2.3.6-4.6
                                                                                                                                                        1.9-6.5
                                                                                                                                                        1.9-2.7
                                                                                                                                                        4.2-5
                                                                                                                                                        7-6.8
                                                                                                                                                        4.2-2.9
                                                                                                                                                        7.9-4.3
                                                                                                                                                        11.1-4.3
                                                                                                                                                        3.2
                                                                                                                                                        0
                                                                                                                                                        6.2
                                                                                                                                                        1.5
                                                                                                                                                        9
                                                                                                                                                        4.6l-9
                                                                                                                                                        7.1c-1.8-2.3-5.2-2.8-7.5-1l-.3.3c-1
                                                                                                                                                        .6-1.7
                                                                                                                                                        1.5-2.1
                                                                                                                                                        2.6-.3.8-.1
                                                                                                                                                        1.7.4
                                                                                                                                                        2.4.4.5
                                                                                                                                                        1
                                                                                                                                                        .9
                                                                                                                                                        1.7.9.8.1
                                                                                                                                                        2.2-.3
                                                                                                                                                        4.2-1.2
                                                                                                                                                        5-2.1
                                                                                                                                                        8.8-3.3
                                                                                                                                                        11.4-3.7
                                                                                                                                                        2.2-.4
                                                                                                                                                        4.5-.2
                                                                                                                                                        6.6.7
                                                                                                                                                        1.9.8
                                                                                                                                                        3.5
                                                                                                                                                        2.2
                                                                                                                                                        4.6
                                                                                                                                                        3.9
                                                                                                                                                        1.4
                                                                                                                                                        2
                                                                                                                                                        2.2
                                                                                                                                                        4.4
                                                                                                                                                        2.3
                                                                                                                                                        6.9.1
                                                                                                                                                        2.6-.6
                                                                                                                                                        5.1-2
                                                                                                                                                        7.3-1.8
                                                                                                                                                        2.7-4.1
                                                                                                                                                        5-6.8
                                                                                                                                                        6.8-5.5
                                                                                                                                                        3.8-10
                                                                                                                                                        5.4-13.6
                                                                                                                                                        4.8-3.9-.6-7.1-2.6-9.4-5.5z"
                                                                                                                                                        /></g></g></g></svg></a></div>
                                                                                                                            </footer>
                                                                                                                        </body>
                                                                                                                    </html>
