<!DOCTYPE html>
<!-- saved from url=(0041)https://alx-intranet.hbtn.io/projects/210 -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <meta name="description" content="">
    <meta name="google" content="notranslate">

    <title>Project: [Optional] Vagrant | ALX Africa Intranet</title>

      <link rel="stylesheet" href="./Project_ [Optional] Vagrant _ ALX Africa Intranet_files/xgz4ilr.css">
      <link rel="stylesheet" media="all" href="./Project_ [Optional] Vagrant _ ALX Africa Intranet_files/application_alx-797565f98971caf22e304b8614ecbc3b779f242f268834e9b46baa0f0eab4c36.css">
      <script async="" src="./Project_ [Optional] Vagrant _ ALX Africa Intranet_files/analytics.js"></script><script src="./Project_ [Optional] Vagrant _ ALX Africa Intranet_files/loader.js"></script>
      <script src="./Project_ [Optional] Vagrant _ ALX Africa Intranet_files/application-fbcf5ccea5ceafdf088aa0038b1711206df04afdbfaa68fdac52645a6794d031.js"></script>
      <link rel="shortcut icon" type="image/x-icon" href="https://alx-intranet.hbtn.io/favicon_alx.ico">
      <meta name="csrf-param" content="authenticity_token">
<meta name="csrf-token" content="XU7uKbn0L8/n3hUEjJlDOwLu241ZG6BlualFP30QfZi43DWhafsoEr+7GQvxmQVhE2V9pAj12SO+a/GC8s26AA==">

      <link rel="apple-touch-icon" href="https://alx-intranet.hbtn.io/apple-touch-icon_alx.png">

      <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
      <!--[if lt IE 9]>
        <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
        <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
      <![endif]-->

      <!-- Store user timezone -->
      <script>
        Cookies.set('timezone', (new Date()).getTimezoneOffset() / -60.0);
      </script>  

      <!-- intro.js for interactive onboarding -->

      <!-- React -->
      <script src="./Project_ [Optional] Vagrant _ ALX Africa Intranet_files/application-8906ffaaef5d4eccdf0b.js"></script>
      <link rel="stylesheet" media="screen" href="./Project_ [Optional] Vagrant _ ALX Africa Intranet_files/application-f61adf9f.css">

  </head>

  <body class="
    signed_in
    env_production
    
    " translate="no" data-theme-suffix="_alx" data-checker-special-theme="">

      <input type="hidden" id="hbtn-slack-url" value="https://alx-students.slack.com">
      <nav class="navbar navbar-default navbar-fixed-top topbar visible-xs">
  <div class="navbar-header">
    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-mobile" aria-expanded="false">
      <span class="sr-only">Toggle navigation</span>
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
    </button>

    <a class="navbar-brand" href="https://alx-intranet.hbtn.io/">
      <div class="logo"></div>
</a>  </div>

  <div class="collapse navbar-collapse navigation" id="navbar-mobile">
    <ul class="nav navbar-nav">
      


    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Planning"><a href="https://alx-intranet.hbtn.io/dashboards/my_planning"><div class="icon "><i aria-hidden="true" class="fa fa-calendar "></i></div><div class="visible-xs">Planning</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-current-projects-item" title="" data-original-title="Projects"><a href="https://alx-intranet.hbtn.io/projects/current"><div class="icon "><i aria-hidden="true" class="fa fa-code-fork "></i></div><div class="visible-xs">Projects</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="My reports"><a href="https://alx-intranet.hbtn.io/users/my_reports"><div class="icon "><i aria-hidden="true" class="fa fa-sticky-note-o "></i></div><div class="visible-xs">My reports</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="QA Reviews I can make"><a href="https://alx-intranet.hbtn.io/corrections/to_review"><div class="icon "><i aria-hidden="true" class="fa fa-check "></i></div><div class="visible-xs">QA Reviews I can make</div></a></li>
    
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Evaluation quizzes"><a href="https://alx-intranet.hbtn.io/dashboards/my_current_evaluation_quizzes"><div class="icon "><i aria-hidden="true" class="fa fa-question "></i></div><div class="visible-xs">Evaluation quizzes</div></a></li>

    <hr title="My resources">

    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Curriculums"><a href="https://alx-intranet.hbtn.io/dashboards/my_curriculums"><div class="icon "><i aria-hidden="true" class="fa fa-graduation-cap "></i></div><div class="visible-xs">Curriculums</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-concepts-item" title="" data-original-title="Concepts"><a href="https://alx-intranet.hbtn.io/concepts"><div class="icon "><i aria-hidden="true" class="fa fa-file-text "></i></div><div class="visible-xs">Concepts</div></a></li>
    
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-video-rooms" title="" data-original-title="Conference rooms"><a href="https://alx-intranet.hbtn.io/dashboards/video_rooms"><div class="icon "><i aria-hidden="true" class="fa fa-comments "></i></div><div class="visible-xs">Conference rooms</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Servers"><a href="https://alx-intranet.hbtn.io/servers"><div class="icon "><i aria-hidden="true" class="fa fa-server "></i></div><div class="visible-xs">Servers</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-my-containers" title="" data-original-title="Sandboxes"><a href="https://alx-intranet.hbtn.io/user_containers/current"><div class="icon "><i aria-hidden="true" class="fa fa-terminal "></i></div><div class="visible-xs">Sandboxes</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Tools"><a href="https://alx-intranet.hbtn.io/dashboards/my_tools"><div class="icon "><i aria-hidden="true" class="fa fa-wrench "></i></div><div class="visible-xs">Tools</div></a></li>
    

      <hr title="My campus">

      
      <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Peers"><a href="https://alx-intranet.hbtn.io/users/peers"><div class="icon "><i aria-hidden="true" class="fa fa-users "></i></div><div class="visible-xs">Peers</div></a></li>
      <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Captain&#39;s Logs"><a href="https://alx-intranet.hbtn.io/dashboards/my_captain_log"><div class="icon "><i aria-hidden="true" class="fa fa-book "></i></div><div class="visible-xs">Captain's Logs</div></a></li>
      
      


<hr class="visible-xs">

<li>
    <div data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Slack">
      <a target="_blank" href="https://alx-students.slack.com/">
        <div class="image slack">
          <div class="inner"></div>
        </div>
        <div class="visible-xs">Slack</div>
</a>    </div>

  <div data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="My Profile">
    <a href="https://alx-intranet.hbtn.io/users/my_profile">
        <div class="image ">
          <div class="inner" style="background-image: url(&#39;https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/000/850/thumb/IMG_20190729_142005.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220422%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220422T223952Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=cf3fca31b02c4f92d3dd917816eb8254d02616fe881827d031ba73e12c75e7c8&#39;)"></div>
        </div>

      <div class="visible-xs">My Profile</div>
</a>  </div>
</li>


    </ul>
  </div>
</nav>

      <div class="hidden-xs navigation sidebar">
  <a class="logo-container" href="https://alx-intranet.hbtn.io/">
    <div class="logo"></div>
</a>
  <ul>
    


    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Planning"><a href="https://alx-intranet.hbtn.io/dashboards/my_planning"><div class="icon "><i aria-hidden="true" class="fa fa-calendar "></i></div><div class="visible-xs">Planning</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-current-projects-item" title="" data-original-title="Projects"><a href="https://alx-intranet.hbtn.io/projects/current"><div class="icon "><i aria-hidden="true" class="fa fa-code-fork "></i></div><div class="visible-xs">Projects</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="My reports"><a href="https://alx-intranet.hbtn.io/users/my_reports"><div class="icon "><i aria-hidden="true" class="fa fa-sticky-note-o "></i></div><div class="visible-xs">My reports</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="QA Reviews I can make"><a href="https://alx-intranet.hbtn.io/corrections/to_review"><div class="icon "><i aria-hidden="true" class="fa fa-check "></i></div><div class="visible-xs">QA Reviews I can make</div></a></li>
    
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Evaluation quizzes"><a href="https://alx-intranet.hbtn.io/dashboards/my_current_evaluation_quizzes"><div class="icon "><i aria-hidden="true" class="fa fa-question "></i></div><div class="visible-xs">Evaluation quizzes</div></a></li>

    <hr title="My resources">

    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Curriculums"><a href="https://alx-intranet.hbtn.io/dashboards/my_curriculums"><div class="icon "><i aria-hidden="true" class="fa fa-graduation-cap "></i></div><div class="visible-xs">Curriculums</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-concepts-item" title="" data-original-title="Concepts"><a href="https://alx-intranet.hbtn.io/concepts"><div class="icon "><i aria-hidden="true" class="fa fa-file-text "></i></div><div class="visible-xs">Concepts</div></a></li>
    
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-video-rooms" title="" data-original-title="Conference rooms"><a href="https://alx-intranet.hbtn.io/dashboards/video_rooms"><div class="icon "><i aria-hidden="true" class="fa fa-comments "></i></div><div class="visible-xs">Conference rooms</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Servers"><a href="https://alx-intranet.hbtn.io/servers"><div class="icon "><i aria-hidden="true" class="fa fa-server "></i></div><div class="visible-xs">Servers</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-my-containers" title="" data-original-title="Sandboxes"><a href="https://alx-intranet.hbtn.io/user_containers/current"><div class="icon "><i aria-hidden="true" class="fa fa-terminal "></i></div><div class="visible-xs">Sandboxes</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Tools"><a href="https://alx-intranet.hbtn.io/dashboards/my_tools"><div class="icon "><i aria-hidden="true" class="fa fa-wrench "></i></div><div class="visible-xs">Tools</div></a></li>
    

      <hr title="My campus">

      
      <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Peers"><a href="https://alx-intranet.hbtn.io/users/peers"><div class="icon "><i aria-hidden="true" class="fa fa-users "></i></div><div class="visible-xs">Peers</div></a></li>
      <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Captain&#39;s Logs"><a href="https://alx-intranet.hbtn.io/dashboards/my_captain_log"><div class="icon "><i aria-hidden="true" class="fa fa-book "></i></div><div class="visible-xs">Captain's Logs</div></a></li>
      
      


<hr class="visible-xs">

<li>
    <div data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Slack">
      <a target="_blank" href="https://alx-students.slack.com/">
        <div class="image slack">
          <div class="inner"></div>
        </div>
        <div class="visible-xs">Slack</div>
</a>    </div>

  <div data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="My Profile">
    <a href="https://alx-intranet.hbtn.io/users/my_profile">
        <div class="image ">
          <div class="inner" style="background-image: url(&#39;https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/000/850/thumb/IMG_20190729_142005.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220422%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220422T223952Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=cf3fca31b02c4f92d3dd917816eb8254d02616fe881827d031ba73e12c75e7c8&#39;)"></div>
        </div>

      <div class="visible-xs">My Profile</div>
</a>  </div>
</li>


  </ul>
</div>


    <main>
      <div id="layout-bars">
        

        

        

        
      </div>

      <article class="">

        
<div class="project row">
  <div class="col-xs-12 col-md-10 col-lg-8 contains-images">

      <h1 class="gap">[Optional] Vagrant</h1>

  <div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[]}" data-react-cache-id="tags/Tags-0"></div>

  <ul class="list-group metadata" id="project-metadata">

    <li class="list-group-item">
      <i aria-hidden="true" class="fa fa-user  fa-fw"></i>
      By Julien Barbier
    </li>

    <li class="list-group-item">
      <i aria-hidden="true" class="fa fa-cogs  fa-fw"></i>
      Weight: 1
    </li>



      <li class="list-group-item">
        <i aria-hidden="true" class="fa fa-calendar  fa-fw"></i>
          Project over - took place from <div data-react-class="common/DateTime" data-react-props="{&quot;showDate&quot;:true,&quot;showTime&quot;:false,&quot;value&quot;:&quot;2021-06-07T06:00:00.000+03:00&quot;}" data-react-cache-id="common/DateTime-0" class="d-inline-block"><span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2021-06-07 04:00 (GMT+01:00)"><span class="datetime">Jun 7, 2021 </span></span></div> to <div data-react-class="common/DateTime" data-react-props="{&quot;showDate&quot;:true,&quot;showTime&quot;:false,&quot;value&quot;:&quot;2021-06-11T06:00:00.000+03:00&quot;}" data-react-cache-id="common/DateTime-0" class="d-inline-block"><span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2021-06-11 04:00 (GMT+01:00)"><span class="datetime">Jun 11, 2021 </span></span></div>
          - you're done with <span id="student_task_done_percentage">100</span>% of tasks.
      </li>



      <li class="list-group-item">
        <i aria-hidden="true" class="fa fa-check-square  fa-fw"></i>
        An auto review will be launched at the deadline
      </li>

      <div class="gap clean well">
  <h4>In a nutshell???</h4>
  <ul>


      <li>
        <strong>Auto QA review:</strong>
          1.0/1 mandatory
            &amp;
            10.0/10 optional
      </li>
    <li>
      <strong>Altogether:</strong>
        &nbsp;<strong>200.0%</strong>
        <ul>
          <li>Mandatory: 100.0%</li>
            <li>Optional: 100.0%</li>
            <li>
              Calculation:&nbsp;
                  100.0%
                    + (100.0% * 100.0%)
              &nbsp;==&nbsp;<strong>200.0%</strong>
            </li>
        </ul>
    </li>
  </ul>
</div>

</ul>




    <div id="project_id" style="display: none" data-project-id="210"></div>




      

        <h2>Concepts</h2>

  <div class="panel panel-default">
    <div class="panel-body">
      <p>
        <em>For this project, students are expected to look at this concept:</em>
      </p>

      <ul>
          <li>
            <a href="https://alx-intranet.hbtn.io/concepts/81">Using Vagrant on your personal computer</a>
          </li>
      </ul>
    </div>
  </div>


      <div class="well clean" id="project-description">
  <h2>Vagrant - or - how to code in your local computer</h2>

<p>Sandboxes are great, but you can also do your ALX assessments on your local computer - having a virtual machine (VM) is the perfect tool for that. </p>

<p>Let???s dig into <strong>Vagrant</strong> today!</p>

<p>Also:</p>

<ul>
<li>This project is <strong>100% optional</strong></li>
<li>This project <strong>can???t be done in Sandboxes</strong> - it can be done only in your local computer.</li>
</ul>

<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="https://alx-intranet.hbtn.io/rltoken/eoV8V_5fgzW_UhJ3PtVyWw" title="Virtual machine" target="_blank">Virtual machine</a> </li>
<li><a href="https://alx-intranet.hbtn.io/rltoken/Z4MowYniH5YJoZo4jZgIBw" title="man uname" target="_blank">man uname</a> </li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="https://alx-intranet.hbtn.io/rltoken/g5OVhHRsT0jjsvUI1Y8jgw" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What is a virtual machine</li>
<li>What is Vagrant</li>
<li>Who wrote Vagrant</li>
<li>What is Ubuntu</li>
<li>What does ???Ubuntu??? mean</li>
<li>How to use VMs with Vagrant</li>
<li>What does the command <code>uname</code> do</li>
</ul>

<h2>Requirements</h2>

<h3>General</h3>

<ul>
<li>A <code>README.md</code> file at the root of the repo, containing a description of the repository</li>
<li>A <code>README.md</code> file, at the root of the folder of <em>this</em> project (i.e. <code>0x00-vagrant</code>), describing what this project is about</li>
</ul>

<h2>More Info</h2>

<h3>Install <code>git</code></h3>

<p>If <code>git</code> is not already installed on your terminal:</p>

<pre><code>$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
</code></pre>

<h3>Basic usage</h3>

<p>At the end of this project you should be able to reproduce and understand these command lines:</p>

<pre><code>$ git clone &lt;repo&gt;
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
</code></pre>

<h3>Warning</h3>

<p>This project <strong>can???t be done in Sandboxes</strong> - it can be done only in your local computer.
Please refer to our concept pages for your operating system.</p>

</div>


      

        <h2 class="gap" id="project-quiz-questions-title">
    Quiz questions
  </h2>


  <div class="panel panel-default">
    <div class="panel-body">
        <div class="alert alert-info">
          <strong>Great!</strong>
          You've completed the quiz successfully! Keep going!
          <span id="quiz_questions_collapse_toggle">(Show quiz)</span>
        </div>

      <section class="quiz_questions_show_container" style="display: none;">
          <div class="quiz_question_item_container" data-role="quiz_question849" data-position="1">
            <div class=" clearfix" id="quiz_question-849">

    <h4 class="quiz_question">
        
        Question #0
    </h4>

    <!-- Quiz question Body -->
    <p>What is a virtual machine?</p>


    <!-- Quiz question Answers -->
        <ul class="quiz_question_answers" data-question-id="849">
                <li class="">
  <input type="checkbox" name="quiz-answer-1557520036929" id="quiz-answer-1557520036929" data-quiz-question-id="849" data-quiz-answer-id="1557520036929" disabled="disabled">
  <label for="quiz-answer-1557520036929">
    <p>A set of servers for software development</p>

</label></li>

                <li class="">
  <input type="checkbox" name="quiz-answer-1557520041317" id="quiz-answer-1557520041317" data-quiz-question-id="849" data-quiz-answer-id="1557520041317" disabled="disabled">
  <label for="quiz-answer-1557520041317">
    <p>A system for developing virtual reality</p>

</label></li>

                <li class="">
  <input type="checkbox" name="quiz-answer-1557520042922" id="quiz-answer-1557520042922" data-quiz-question-id="849" data-quiz-answer-id="1557520042922" disabled="disabled" checked="checked">
  <label for="quiz-answer-1557520042922">
    <p>An emulation of a computer system</p>

</label></li>

        </ul>

    <!-- Quiz question Tips -->

</div>

          </div>
          <div class="quiz_question_item_container" data-role="quiz_question850" data-position="2">
            <div class=" clearfix" id="quiz_question-850">

    <h4 class="quiz_question">
        
        Question #1
    </h4>

    <!-- Quiz question Body -->
    <p>Ubuntu is a ____ distribution.</p>


    <!-- Quiz question Answers -->
        <ul class="quiz_question_answers" data-question-id="850">
                <li class="">
  <input type="checkbox" name="quiz-answer-1557520149027" id="quiz-answer-1557520149027" data-quiz-question-id="850" data-quiz-answer-id="1557520149027" disabled="disabled">
  <label for="quiz-answer-1557520149027">
    <p>Windows</p>

</label></li>

                <li class="">
  <input type="checkbox" name="quiz-answer-1557520150003" id="quiz-answer-1557520150003" data-quiz-question-id="850" data-quiz-answer-id="1557520150003" disabled="disabled" checked="checked">
  <label for="quiz-answer-1557520150003">
    <p>Linux</p>

</label></li>

                <li class="">
  <input type="checkbox" name="quiz-answer-1557520151141" id="quiz-answer-1557520151141" data-quiz-question-id="850" data-quiz-answer-id="1557520151141" disabled="disabled">
  <label for="quiz-answer-1557520151141">
    <p>MacOS</p>

</label></li>

        </ul>

    <!-- Quiz question Tips -->

</div>

          </div>

      </section>
    </div>
  </div>


        
          <h2 class="gap">Tasks</h2>

    <div data-role="task3902" data-position="1" id="task-num-0">
      <div class="panel panel-default task-card " id="task-3902">
  <span id="user_id" data-id="850"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      0. Create and setup your Git and GitHub account
    </h3>

    <div>
        <span class="label label-info">
          #advanced
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="850"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="3902" data-correction-id="13071">
        <div class="task_progress_bar" style="width: 100%;">
          <div class="task_score_bar" style="width: 100%;">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">100.00%</span> (<span class="task_progress_value">Checks completed: 100.00%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>You will need Git for this project, you might have to <a href="https://alx-intranet.hbtn.io/rltoken/7kPsched1VMPOY2bdvZvGQ" title="install it" target="_blank">install it</a> on your computer if it???s not done yet.</p>

<ul>
<li>Configure your basic info (name, email) on your local machine ??? they will be part of your commits. <a href="https://alx-intranet.hbtn.io/rltoken/oAAqmPJ1ftZZhUjaw7FvjA" title="Tips" target="_blank">Tips</a></li>
</ul>

<p>On <a href="https://alx-intranet.hbtn.io/rltoken/4vp5Qze3WATHKtytzT2_UA" title="GitHub.com" target="_blank">GitHub.com</a>:</p>

<ul>
<li>Using the graphic interface on the website, create the repository (if it???s not done yet)

<ul>
<li>Description: <code>This is my first repository as a full-stack engineer</code></li>
<li>Public repo: <code>zero_day</code></li>
<li>No <code>README</code>, <code>.gitignore</code>, or license</li>
</ul></li>
</ul>

<p>On your computer, open a terminal and do the following:</p>

<ul>
<li>Navigate to your home directory. <a href="https://alx-intranet.hbtn.io/rltoken/YeOwsN-vhfSCbNjgE01Gag" title="Tips" target="_blank">Tips</a></li>
<li>Create a directory <code>zero_day</code>. <a href="https://alx-intranet.hbtn.io/rltoken/hWrqqlilEv8L6yqpyt1TTA" title="Tips" target="_blank">Tips</a></li>
<li>Navigate to this new directory. <a href="https://alx-intranet.hbtn.io/rltoken/za58mq537U6U775osQ8bfQ" title="Tips" target="_blank">Tips</a></li>
<li>Initialize git and add the remote origin</li>
<li>Create a file <code>README.md</code> with Emacs (or other command line editors) and write a small <a href="https://alx-intranet.hbtn.io/rltoken/VV79mKOEf5mXVbKpH4i63Q" title="Markdown" target="_blank">Markdown</a> text to present this project. <strong>This file is mandatory in projects</strong></li>
<li>Add this new file to git, commit the change with this message ???My first commit??? and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)</li>
</ul>

<p>Good job! </p>

<p>You pushed your first file in your <strong>first repository</strong> of the <strong>first task</strong> of your <strong>first School project</strong>.</p>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>zero_day</code></li>
            <li>File: <code>README.md</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm yes" data-task-id="3902">
      <span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

    <button class="users_done_for_task btn btn-default btn-sm" data-task-id="3902" data-project-id="210" data-toggle="modal" data-target="#task-3902-users-done-modal">
      Help
    </button>
    <div class="modal fade users-done-modal" id="task-3902-users-done-modal" data-task-id="3902" data-project-id="210">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">??</span></button>
            <h4 class="modal-title">Students who are done with "0. Create and setup your Git and GitHub account"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


      <button class="btn btn-default btn-sm" data-task-id="3902" data-toggle="modal" data-target="#task-test-correction-3902-correction-modal" id="task-num-0-check-code-btn">Re-check your code</button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-3902-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">??</span></button>
                <h4 class="modal-title">Correction of "0. Create and setup your Git and GitHub account"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="3902">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>


                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="3902">
        <i aria-hidden="true" class="fa fa-info-circle "></i>
    </button>
    <div class="help-container" data-task-id="3902">
        <div class="check-line">
            <div class="check-inline requirement success">
                  <i aria-hidden="true" class="fa fa-check-circle "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                  <i aria-hidden="true" class="fa fa-times-circle "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                  <i aria-hidden="true" class="fa fa-check-circle "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                  <i aria-hidden="true" class="fa fa-times-circle "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                  <i aria-hidden="true" class="fa fa-check-circle "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                  <i aria-hidden="true" class="fa fa-times-circle "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                  <i aria-hidden="true" class="fa fa-check-circle "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                  <i aria-hidden="true" class="fa fa-times-circle "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                  <i aria-hidden="true" class="fa fa-times-circle "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div><!-- /.modal-content -->
    </div><!-- /.modal-dialog -->
</div>



    

      <button class="btn btn-default btn-sm" data-task-id="3902" data-toggle="modal" data-target="#task-qa-review-3902-modal">
        QA Review
      </button>
      <div class="modal fade task_get_qa_review" id="task-qa-review-3902-modal" data-correction-id="13071" data-task-id="3902">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">??</span></button>
                <h4 class="modal-title">0. Create and setup your Git and GitHub account</h4>
            </div>
            <div class="modal-body">
                <div class="spinner gap">
                    <div class="bounce1"></div>
                    <div class="bounce2"></div>
                    <div class="bounce3"></div>
                </div>
                <div class="review-container">
                    <div class="review-corrector"></div>
                    <div class="review-github well" style="display:none">
                        <h5>Commit used:</h5>
                        <ul>
                            <li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
                            <li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
                            <li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
                            <li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
                            <li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
                            <li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
                        </ul>
                    </div>
                    <div class="review-percentage_down"></div>
                    <ul class="review-checks list-group sm-gap"></ul>
                    <div class="review-comment"></div>
                </div>
            </div>
        </div>
    </div>
</div>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task808" data-position="2" id="task-num-1">
      <div class="panel panel-default task-card " id="task-808">
  <span id="user_id" data-id="850"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      1. Hello Ubuntu
    </h3>

    <div>
        <span class="label label-info">
          #advanced
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="850"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="808" data-correction-id="13071">
        <div class="task_progress_bar" style="width: 100%;">
          <div class="task_score_bar" style="width: 100%;">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">100.00%</span> (<span class="task_progress_value">Checks completed: 100.00%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>Inside the <code>zero_day</code> repo, create a new directory called <code>0x00-vagrant</code>. Add a <code>README.md</code> file to this directory. </p>

<p><code>ssh</code> into your Ubuntu VM. What does the command <code>uname</code> print when you run it without any option? </p>

<p>Type your answer into a file in the <code>0x00-vagrant</code> directory and push it to GitHub. Name your file accordingly as shown below.</p>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>zero_day</code></li>
            <li>Directory: <code>0x00-vagrant</code></li>
            <li>File: <code>0-hello_ubuntu</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm yes" data-task-id="808">
      <span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

    <button class="users_done_for_task btn btn-default btn-sm" data-task-id="808" data-project-id="210" data-toggle="modal" data-target="#task-808-users-done-modal">
      Help
    </button>
    <div class="modal fade users-done-modal" id="task-808-users-done-modal" data-task-id="808" data-project-id="210">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">??</span></button>
            <h4 class="modal-title">Students who are done with "1. Hello Ubuntu"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


      <button class="btn btn-default btn-sm" data-task-id="808" data-toggle="modal" data-target="#task-test-correction-808-correction-modal" id="task-num-1-check-code-btn">Re-check your code</button>
      <div class="modal fade task_correction_modal student_modal" id="task-test-correction-808-correction-modal">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">??</span></button>
                <h4 class="modal-title">Correction of "1. Hello Ubuntu"</h4>
            </div>
            <div class="modal-body">
                <div class="actions">
                    <center>
                        <div class="alert alert-info hidden"></div>

                        <button name="button" type="submit" class="btn btn-primary correction_request_test_send" data-task-id="808">Start a new test</button>
                        <button class="btn btn-default close-modal hidden" data-dismiss="modal" type="button">Close</button>

                        <div class="spinner" style="display: none;">
                            <div class="bounce1"></div>
                            <div class="bounce2"></div>
                            <div class="bounce3"></div>
                        </div>
                        <div class="error"></div>
                        <div class="info"></div>


                    </center>
                </div>
                <div class="result"></div>

                <div class="help">
    <button data-task-id="808">
        <i aria-hidden="true" class="fa fa-info-circle "></i>
    </button>
    <div class="help-container" data-task-id="808">
        <div class="check-line">
            <div class="check-inline requirement success">
                  <i aria-hidden="true" class="fa fa-check-circle "></i>
                Requirement success
            </div>
            <div class="check-inline requirement fail">
                  <i aria-hidden="true" class="fa fa-times-circle "></i>
                Requirement fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline code success">
                  <i aria-hidden="true" class="fa fa-check-circle "></i>
                Code success
            </div>
            <div class="check-inline code fail">
                  <i aria-hidden="true" class="fa fa-times-circle "></i>
                Code fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline efficiency success">
                  <i aria-hidden="true" class="fa fa-check-circle "></i>
                Efficiency success
            </div>
            <div class="check-inline efficiency fail">
                  <i aria-hidden="true" class="fa fa-times-circle "></i>
                Efficiency fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline answer success">
                  <i aria-hidden="true" class="fa fa-check-circle "></i>
                Text answer success
            </div>
            <div class="check-inline answer fail">
                  <i aria-hidden="true" class="fa fa-times-circle "></i>
                Text answer fail
            </div>
        </div>
        <div class="check-line">
            <div class="check-inline requirement fail offline">
                  <i aria-hidden="true" class="fa fa-times-circle "></i>
                Skipped - Previous check failed
            </div>
        </div>
    </div>
</div>

            </div>
        </div><!-- /.modal-content -->
    </div><!-- /.modal-dialog -->
</div>



    

      <button class="btn btn-default btn-sm" data-task-id="808" data-toggle="modal" data-target="#task-qa-review-808-modal">
        QA Review
      </button>
      <div class="modal fade task_get_qa_review" id="task-qa-review-808-modal" data-correction-id="13071" data-task-id="808">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">??</span></button>
                <h4 class="modal-title">1. Hello Ubuntu</h4>
            </div>
            <div class="modal-body">
                <div class="spinner gap">
                    <div class="bounce1"></div>
                    <div class="bounce2"></div>
                    <div class="bounce3"></div>
                </div>
                <div class="review-container">
                    <div class="review-corrector"></div>
                    <div class="review-github well" style="display:none">
                        <h5>Commit used:</h5>
                        <ul>
                            <li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
                            <li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
                            <li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
                            <li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
                            <li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
                            <li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
                        </ul>
                    </div>
                    <div class="review-percentage_down"></div>
                    <ul class="review-checks list-group sm-gap"></ul>
                    <div class="review-comment"></div>
                </div>
            </div>
        </div>
    </div>
</div>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>







  </div>
</div>


      </article>

      <div class="copyright">Copyright ?? 2022 ALX, All rights reserved.</div>
    </main>

      <button class="btn btn-primary" id="search-button" data-search-active="false" data-toggle="modal" data-target="#search-modal">
  <i aria-hidden="true" class="fa fa-search "></i>
  <i aria-hidden="true" class="fa fa-window-minimize "></i>
</button>

      <div class="modal fade" id="search-modal" tabindex="-1" role="dialog" aria-labelledby="search-modal-label">
    <div class="modal-dialog modal-md">
        <div class="modal-content">
            <div class="modal-header">
                <div id="search-bar-container">
    <input id="search-bar" type="text" name="hbtn-search-bar" placeholder="???Start search by typing in this field???">
</div>

            </div>
            <div class="modal-body">
                <div id="modal-spinner" class="spinner gap">
                    <div class="bounce1"></div>
                    <div class="bounce2"></div>
                    <div class="bounce3"></div>
                </div>
                <div id="search-results-container">
</div>

            </div>
        </div>
    </div>
</div>



      <div class="modal fade" id="markdownGuideModal" tabindex="-1" role="dialog" aria-labelledby="markdownGuideModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-md">
    <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">??</span></button>
          <h4 class="modal-title">Markdown Guide</h4>
        </div>
        <div class="modal-body">
            <h4>Emphasis</h4>
<pre>**<strong>bold</strong>**
*<em>italics</em>*
~~<strike>strikethrough</strike>~~</pre>
<h4>Headers</h4>
<pre># Big header
## Medium header
### Small header
#### Tiny header</pre>
<h4>Lists</h4>
<pre>* Generic list item
* Generic list item
* Generic list item

1. Numbered list item
2. Numbered list item
3. Numbered list item</pre>
<h4>Links</h4>
<pre>[Text to display](http://www.example.com)</pre>
<h4>Quotes</h4>
<pre>&gt; This is a quote.
&gt; It can span multiple lines!</pre>
<h4>Images</h4>
<p>CSS style available: <code>width, height, opacity</code></p>
<pre>![](http://www.example.com/image.jpg)
![](http://www.example.com/image.jpg | width: 200px)
![](http://www.example.com/image.jpg | height: 124px | width: 80px | opacity: 0.6)
</pre>
<h4>Tables</h4>
<pre>| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John     | Doe      | Male     |
| Mary     | Smith    | Female   |

<em>Or without aligning the columns...</em>

| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John | Doe | Male |
| Mary | Smith | Female |
</pre>
<h4>Displaying code</h4>
<pre>`var example = "hello!";`

<em>Or spanning multiple lines...</em>

```
var example = "hello!";
alert(example);
```</pre>
        </div>
    </div>
  </div>
</div>


      <script>
        (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
        (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
        m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
        })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

          ga('create',
            'UA-67152800-9',
            'auto', {
              userId: '850'
            }
          );

        ga('send', 'pageview');

        $(document).ready(function() {
          ga(function(tracker) {
            var clientId = tracker.get('clientId');
            $('.ga-client-id').val(clientId);
          });
        });
      </script>




      


  

</body></html>
