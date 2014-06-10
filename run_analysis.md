




<!DOCTYPE html>
<html class="   ">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    
    
    <title>GettingAndCleaningData/Project/run_analysis.md at master · gisontherun/GettingAndCleaningData</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub" />
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png" />
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png" />
    <meta property="fb:app_id" content="1401488693436528"/>

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="gisontherun/GettingAndCleaningData" name="twitter:title" /><meta content="Contribute to GettingAndCleaningData development by creating an account on GitHub." name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/1897044?s=400" name="twitter:image:src" />
<meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/1897044?s=400" property="og:image" /><meta content="gisontherun/GettingAndCleaningData" property="og:title" /><meta content="https://github.com/gisontherun/GettingAndCleaningData" property="og:url" /><meta content="Contribute to GettingAndCleaningData development by creating an account on GitHub." property="og:description" />

    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="conduit-xhr" href="https://ghconduit.com:25035">
    <link rel="xhr-socket" href="/_sockets" />

    <meta name="msapplication-TileImage" content="/windows-tile.png" />
    <meta name="msapplication-TileColor" content="#ffffff" />
    <meta name="selected-link" value="repo_source" data-pjax-transient />
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector-new.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="5F233A23:4762:6CB6D6B:5396A59A" name="octolytics-dimension-request_id" /><meta content="7278335" name="octolytics-actor-id" /><meta content="gisontherun" name="octolytics-actor-login" /><meta content="a0e6d0ce41ffadb092493282097eaaec8ad5162cdf612990cffc096f583c6c2d" name="octolytics-actor-hash" />
    

    
    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico" />


    <meta content="authenticity_token" name="csrf-param" />
<meta content="EN8Ndbsasq0emegDY0P+UUe5Vmg1pncIA1bFNAXhanJAj0fpl8eOfXGAQ3FEvhE5aPYm05yyRH7PwHaAdThFgw==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-1aeb426322c64c12b92d56bda5b110fc1093f75e.css" media="all" rel="stylesheet" type="text/css" />
    <link href="https://assets-cdn.github.com/assets/github2-b2cccfcac1a522b6ce675606f61388d36bf2c080.css" media="all" rel="stylesheet" type="text/css" />
    


    <meta http-equiv="x-pjax-version" content="fdaba147338e2f71f6dadeadf7941995">

      
  <meta name="description" content="Contribute to GettingAndCleaningData development by creating an account on GitHub." />

  <meta content="1897044" name="octolytics-dimension-user_id" /><meta content="gisontherun" name="octolytics-dimension-user_login" /><meta content="18577753" name="octolytics-dimension-repository_id" /><meta content="gisontherun/GettingAndCleaningData" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="18577753" name="octolytics-dimension-repository_network_root_id" /><meta content="gisontherun/GettingAndCleaningData" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/gisontherun/GettingAndCleaningData/commits/master.atom" rel="alternate" title="Recent Commits to GettingAndCleaningData:master" type="application/atom+xml" />

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      
      


      <div class="header header-logged-in true">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/">
  <span class="mega-octicon octicon-mark-github"></span>
</a>

    
    <a href="/notifications" aria-label="You have no unread notifications" class="notification-indicator tooltipped tooltipped-s" data-hotkey="g n">
        <span class="mail-status all-read"></span>
</a>

      <div class="command-bar js-command-bar  in-repository">
          <form accept-charset="UTF-8" action="/search" class="command-bar-form" id="top_search_form" method="get">

<div class="commandbar">
  <span class="message"></span>
  <input type="text" data-hotkey="s, /" name="q" id="js-command-bar-field" placeholder="Search or type a command" tabindex="1" autocapitalize="off"
    
    data-username="gisontherun"
      data-repo="gisontherun/GettingAndCleaningData"
      data-branch="master"
      data-sha="ab742db84d2eb8f09796864d4f2a09900384aa5e"
  >
  <div class="display hidden"></div>
</div>

    <input type="hidden" name="nwo" value="gisontherun/GettingAndCleaningData" />

    <div class="select-menu js-menu-container js-select-menu search-context-select-menu">
      <span class="minibutton select-menu-button js-menu-target" role="button" aria-haspopup="true">
        <span class="js-select-button">This repository</span>
      </span>

      <div class="select-menu-modal-holder js-menu-content js-navigation-container" aria-hidden="true">
        <div class="select-menu-modal">

          <div class="select-menu-item js-navigation-item js-this-repository-navigation-item selected">
            <span class="select-menu-item-icon octicon octicon-check"></span>
            <input type="radio" class="js-search-this-repository" name="search_target" value="repository" checked="checked" />
            <div class="select-menu-item-text js-select-button-text">This repository</div>
          </div> <!-- /.select-menu-item -->

          <div class="select-menu-item js-navigation-item js-all-repositories-navigation-item">
            <span class="select-menu-item-icon octicon octicon-check"></span>
            <input type="radio" name="search_target" value="global" />
            <div class="select-menu-item-text js-select-button-text">All repositories</div>
          </div> <!-- /.select-menu-item -->

        </div>
      </div>
    </div>

  <span class="help tooltipped tooltipped-s" aria-label="Show command bar help">
    <span class="octicon octicon-question"></span>
  </span>


  <input type="hidden" name="ref" value="cmdform">

</form>
        <ul class="top-nav">
          <li class="explore"><a href="/explore">Explore</a></li>
            <li><a href="https://gist.github.com">Gist</a></li>
            <li><a href="/blog">Blog</a></li>
          <li><a href="https://help.github.com">Help</a></li>
        </ul>
      </div>

    


  <ul id="user-links">
    <li>
      <a href="/gisontherun" class="name">
        <img alt="" class=" js-avatar" data-user="7278335" height="20" src="https://avatars3.githubusercontent.com/u/7278335?s=140" width="20" /> gisontherun
      </a>
    </li>

    <li class="new-menu dropdown-toggle js-menu-container">
      <a href="#" class="js-menu-target tooltipped tooltipped-s" aria-label="Create new...">
        <span class="octicon octicon-plus"></span>
        <span class="dropdown-arrow"></span>
      </a>

      <div class="new-menu-content js-menu-content">
      </div>
    </li>

    <li>
      <a href="/settings/profile" id="account_settings"
        class="tooltipped tooltipped-s"
        aria-label="Account settings ">
        <span class="octicon octicon-tools"></span>
      </a>
    </li>
    <li>
      <form class="logout-form" action="/logout" method="post">
        <button class="sign-out-button tooltipped tooltipped-s" aria-label="Sign out">
          <span class="octicon octicon-sign-out"></span>
        </button>
      </form>
    </li>

  </ul>

<div class="js-new-dropdown-contents hidden">
  

<ul class="dropdown-menu">
  <li>
    <a href="/new"><span class="octicon octicon-repo"></span> New repository</a>
  </li>
  <li>
    <a href="/organizations/new"><span class="octicon octicon-organization"></span> New organization</a>
  </li>


    <li class="section-title">
      <span title="gisontherun/GettingAndCleaningData">This repository</span>
    </li>
      <li>
        <a href="/gisontherun/GettingAndCleaningData/issues/new"><span class="octicon octicon-issue-opened"></span> New issue</a>
      </li>
</ul>

</div>


    
  </div>
</div>

      

        



      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        

<ul class="pagehead-actions">

    <li class="subscription">
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="authenticity_token" type="hidden" value="EX/TaRaaHvZJ9AWSRHhJK8nD/EJXcKNJo19UgMTJKJ/QtUduK9uXL3xGorEtTODYCXTnK1QWWnJs8TMkI6ZYCA==" /></div>  <input id="repository_id" name="repository_id" type="hidden" value="18577753" />

    <div class="select-menu js-menu-container js-select-menu">
      <a class="social-count js-social-count" href="/gisontherun/GettingAndCleaningData/watchers">
        2
      </a>
      <span class="minibutton select-menu-button with-count js-menu-target" role="button" tabindex="0" aria-haspopup="true">
        <span class="js-select-button">
          <span class="octicon octicon-eye"></span>
          Watch
        </span>
      </span>

      <div class="select-menu-modal-holder">
        <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
          <div class="select-menu-header">
            <span class="select-menu-title">Notification status</span>
            <span class="octicon octicon-x js-menu-close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-list js-navigation-container" role="menu">

            <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                <h4>Not watching</h4>
                <span class="description">You only receive notifications for conversations in which you participate or are @mentioned.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Watch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                <h4>Watching</h4>
                <span class="description">You receive notifications for all conversations in this repository.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Unwatch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_ignore" name="do" type="radio" value="ignore" />
                <h4>Ignoring</h4>
                <span class="description">You do not receive any notifications for conversations in this repository.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-mute"></span>
                  Stop ignoring
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

          </div> <!-- /.select-menu-list -->

        </div> <!-- /.select-menu-modal -->
      </div> <!-- /.select-menu-modal-holder -->
    </div> <!-- /.select-menu -->

</form>
    </li>

  <li>
  

  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/gisontherun/GettingAndCleaningData/unstar" class="js-toggler-form starred" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="authenticity_token" type="hidden" value="z9oOZwHIzv+T1FLVcKkn+jA5SP/RDDr5UCkTTRhB601GGjDW9TF+m2bVaCSe2uIKsW62PaawLfvuh6xWw5wevA==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Unstar this repository" title="Unstar gisontherun/GettingAndCleaningData">
        <span class="octicon octicon-star"></span><span class="text">Unstar</span>
      </button>
        <a class="social-count js-social-count" href="/gisontherun/GettingAndCleaningData/stargazers">
          2
        </a>
</form>
    <form accept-charset="UTF-8" action="/gisontherun/GettingAndCleaningData/star" class="js-toggler-form unstarred" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="authenticity_token" type="hidden" value="08PQpriWp7e4Z8UHqWtCGAQ8aoJ/TbcS6d3o0kCVgMIARrnOvStZURfroY70e1iU7xe1TkNZNCkNcqqFzX1bUQ==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Star this repository" title="Star gisontherun/GettingAndCleaningData">
        <span class="octicon octicon-star"></span><span class="text">Star</span>
      </button>
        <a class="social-count js-social-count" href="/gisontherun/GettingAndCleaningData/stargazers">
          2
        </a>
</form>  </div>

  </li>


        <li>
          <a href="/gisontherun/GettingAndCleaningData/fork" class="minibutton with-count js-toggler-target fork-button lighter tooltipped-n" title="Fork your own copy of gisontherun/GettingAndCleaningData to your account" aria-label="Fork your own copy of gisontherun/GettingAndCleaningData to your account" rel="nofollow" data-method="post">
            <span class="octicon octicon-repo-forked"></span><span class="text">Fork</span>
          </a>
          <a href="/gisontherun/GettingAndCleaningData/network" class="social-count">10</a>
        </li>


</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="repo-label"><span>public</span></span>
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/gisontherun" class="url fn" itemprop="url" rel="author"><span itemprop="title">gisontherun</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/gisontherun/GettingAndCleaningData" class="js-current-repository js-repo-home-link">GettingAndCleaningData</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline js-new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            

<div class="sunken-menu vertical-right repo-nav js-repo-nav js-repository-container-pjax js-octicon-loaders">
  <div class="sunken-menu-contents">
    <ul class="sunken-menu-group">
      <li class="tooltipped tooltipped-w" aria-label="Code">
        <a href="/gisontherun/GettingAndCleaningData" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-pjax="true" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /gisontherun/GettingAndCleaningData">
          <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

        <li class="tooltipped tooltipped-w" aria-label="Issues">
          <a href="/gisontherun/GettingAndCleaningData/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g i" data-selected-links="repo_issues /gisontherun/GettingAndCleaningData/issues">
            <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
            <span class='counter'>0</span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>

      <li class="tooltipped tooltipped-w" aria-label="Pull Requests">
        <a href="/gisontherun/GettingAndCleaningData/pulls" aria-label="Pull Requests" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g p" data-selected-links="repo_pulls /gisontherun/GettingAndCleaningData/pulls">
            <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull Requests</span>
            <span class='counter'>0</span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>


        <li class="tooltipped tooltipped-w" aria-label="Wiki">
          <a href="/gisontherun/GettingAndCleaningData/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g w" data-selected-links="repo_wiki /gisontherun/GettingAndCleaningData/wiki">
            <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>
    </ul>
    <div class="sunken-menu-separator"></div>
    <ul class="sunken-menu-group">

      <li class="tooltipped tooltipped-w" aria-label="Pulse">
        <a href="/gisontherun/GettingAndCleaningData/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-pjax="true" data-selected-links="pulse /gisontherun/GettingAndCleaningData/pulse">
          <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

      <li class="tooltipped tooltipped-w" aria-label="Graphs">
        <a href="/gisontherun/GettingAndCleaningData/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-pjax="true" data-selected-links="repo_graphs repo_contributors /gisontherun/GettingAndCleaningData/graphs">
          <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

      <li class="tooltipped tooltipped-w" aria-label="Network">
        <a href="/gisontherun/GettingAndCleaningData/network" aria-label="Network" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-selected-links="repo_network /gisontherun/GettingAndCleaningData/network">
          <span class="octicon octicon-repo-forked"></span> <span class="full-word">Network</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
    </ul>


  </div>
</div>

              <div class="only-with-full-nav">
                

  

<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><strong>HTTPS</strong> clone URL</h3>
  <div class="clone-url-box">
    <input type="text" class="clone js-url-field"
           value="https://github.com/gisontherun/GettingAndCleaningData.git" readonly="readonly">
    <span class="url-box-clippy">
    <button aria-label="copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="https://github.com/gisontherun/GettingAndCleaningData.git" data-copied-hint="copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  

<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><strong>SSH</strong> clone URL</h3>
  <div class="clone-url-box">
    <input type="text" class="clone js-url-field"
           value="git@github.com:gisontherun/GettingAndCleaningData.git" readonly="readonly">
    <span class="url-box-clippy">
    <button aria-label="copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="git@github.com:gisontherun/GettingAndCleaningData.git" data-copied-hint="copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  

<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><strong>Subversion</strong> checkout URL</h3>
  <div class="clone-url-box">
    <input type="text" class="clone js-url-field"
           value="https://github.com/gisontherun/GettingAndCleaningData" readonly="readonly">
    <span class="url-box-clippy">
    <button aria-label="copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="https://github.com/gisontherun/GettingAndCleaningData" data-copied-hint="copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>


<p class="clone-options">You can clone with
      <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>,
      <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>,
      or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <span class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <a href="https://help.github.com/articles/which-remote-url-should-i-use">
    <span class="octicon octicon-question"></span>
    </a>
  </span>
</p>


  <a href="http://windows.github.com" class="minibutton sidebar-button" title="Save gisontherun/GettingAndCleaningData to your computer and use it in GitHub Desktop." aria-label="Save gisontherun/GettingAndCleaningData to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>

                <a href="/gisontherun/GettingAndCleaningData/archive/master.zip"
                   class="minibutton sidebar-button"
                   aria-label="Download gisontherun/GettingAndCleaningData as a zip file"
                   title="Download gisontherun/GettingAndCleaningData as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          


<a href="/gisontherun/GettingAndCleaningData/blob/eb401a34579a545bc64fedd8d410bdf8ecb6f992/Project/run_analysis.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:99c4d3d4bd308ca13a5c1bc5358729fb -->

<p title="This is a placeholder element" class="js-history-link-replace hidden"></p>

<a href="/gisontherun/GettingAndCleaningData/find/master" data-pjax data-hotkey="t" class="js-show-file-finder" style="display:none">Show File Finder</a>

<div class="file-navigation">
  

<div class="select-menu js-menu-container js-select-menu" >
  <span class="minibutton select-menu-button js-menu-target" data-hotkey="w"
    data-master-branch="master"
    data-ref="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close"></span>
      </div> <!-- /.select-menu-header -->

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div><!-- /.select-menu-tabs -->
      </div><!-- /.select-menu-filters -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <div class="select-menu-item js-navigation-item selected">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/gisontherun/GettingAndCleaningData/blob/master/Project/run_analysis.md"
                 data-name="master"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text js-select-button-text css-truncate-target"
                 title="master">master</a>
            </div> <!-- /.select-menu-item -->
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

    </div> <!-- /.select-menu-modal -->
  </div> <!-- /.select-menu-modal-holder -->
</div> <!-- /.select-menu -->

  <div class="breadcrumb">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/gisontherun/GettingAndCleaningData" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">GettingAndCleaningData</span></a></span></span><span class="separator"> / </span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/gisontherun/GettingAndCleaningData/tree/master/Project" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">Project</span></a></span><span class="separator"> / </span><strong class="final-path">run_analysis.md</strong> <button aria-label="copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="Project/run_analysis.md" data-copied-hint="copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>
</div>


  <div class="commit file-history-tease">
      <img alt="" class="main-avatar" height="24" src="https://0.gravatar.com/avatar/fccfd78eb90b1591caaa7f6f01bd0fcd?d=https%3A%2F%2Fassets-cdn.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png&amp;r=x&amp;s=140" width="24" />
      <span class="author"><span>Benjamin Chan</span></span>
      <time datetime="2014-04-17T09:10:14-07:00" is="relative-time">April 17, 2014</time>
      <div class="commit-title">
          <a href="/gisontherun/GettingAndCleaningData/commit/73f0abb7e5bd770a824ee189e21830c7485c5f1a" class="message" data-pjax="true" title="Add codebook.html">Add codebook.html</a>
      </div>

    <div class="participation">
      <p class="quickstat"><a href="#blob_contributors_box" rel="facebox"><strong>1</strong>  contributor</a></p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="Benjamin Chan" class=" js-avatar" data-user="1897044" height="24" src="https://avatars0.githubusercontent.com/u/1897044?s=140" width="24" />
            <a href="/gisontherun">gisontherun</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file-box">
  <div class="file">
    <div class="meta clearfix">
      <div class="info file-name">
        <span class="icon"><b class="octicon octicon-file-text"></b></span>
        <span class="mode" title="File Mode">file</span>
        <span class="meta-divider"></span>
          <span>402 lines (268 sloc)</span>
          <span class="meta-divider"></span>
        <span>11.631 kb</span>
      </div>
      <div class="actions">
        <div class="button-group">
            <a class="minibutton tooltipped tooltipped-w"
               href="http://windows.github.com" aria-label="Open this file in GitHub for Windows">
                <span class="octicon octicon-device-desktop"></span> Open
            </a>
                <a class="minibutton tooltipped tooltipped-n js-update-url-with-hash"
                   aria-label="Clicking this button will automatically fork this project so you can edit the file"
                   href="/gisontherun/GettingAndCleaningData/edit/master/Project/run_analysis.md"
                   data-method="post" rel="nofollow">Edit</a>
          <a href="/gisontherun/GettingAndCleaningData/raw/master/Project/run_analysis.md" class="button minibutton " id="raw-url">Raw</a>
            <a href="/gisontherun/GettingAndCleaningData/blame/master/Project/run_analysis.md" class="button minibutton js-update-url-with-hash">Blame</a>
          <a href="/gisontherun/GettingAndCleaningData/commits/master/Project/run_analysis.md" class="button minibutton " rel="nofollow">History</a>
        </div><!-- /.button-group -->

            <a class="minibutton danger empty-icon tooltipped tooltipped-s"
               href="/gisontherun/GettingAndCleaningData/delete/master/Project/run_analysis.md"
               aria-label="Fork this project and delete file"
               data-method="post" data-test-id="delete-blob-file" rel="nofollow">

          Delete
        </a>
      </div><!-- /.actions -->
    </div>
      
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a name="user-content-run_analysis" class="anchor" href="#run_analysis"><span class="octicon octicon-link"></span></a>run_analysis</h1>

<p>Last updated 2014-04-17 09:04:14 using R version 3.0.2 (2013-09-25).</p>

<h2>
<a name="user-content-instructions-for-project" class="anchor" href="#instructions-for-project"><span class="octicon octicon-link"></span></a>Instructions for project</h2>

<blockquote>
<p>The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.  </p>

<p>One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: </p>

<p><a href="http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones">http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones</a> </p>

<p>Here are the data for the project: </p>

<p><a href="https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip">https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip</a> </p>

<p>You should create one R script called run_analysis.R that does the following. </p>

<ol class="task-list">
<li>
<strong>DONE</strong> Merges the training and the test sets to create one data set.</li>
<li>
<strong>DONE</strong> Extracts only the measurements on the mean and standard deviation for each measurement.</li>
<li>
<strong>DONE</strong> Uses descriptive activity names to name the activities in the data set.</li>
<li>
<strong>DONE</strong> Appropriately labels the data set with descriptive activity names.</li>
<li>
<strong>DONE</strong> Creates a second, independent tidy data set with the average of each variable for each activity and each subject. </li>
</ol>
<p>Good luck!</p>
</blockquote>

<p><strong>The codebook is at the end of this document.</strong></p>

<h2>
<a name="user-content-preliminaries" class="anchor" href="#preliminaries"><span class="octicon octicon-link"></span></a>Preliminaries</h2>

<p>Load packages.</p>

<div class="highlight highlight-r"><pre><span class="c">packages &lt;- c("data.table", "reshape2")</span>
<span class="c">sapply(packages, require, character.only = TRUE, quietly = TRUE)</span>
</pre></div>

<pre><code>## data.table   reshape2 
##       TRUE       TRUE
</code></pre>

<p>Set path.</p>

<div class="highlight highlight-r"><pre><span class="c">path &lt;- getwd()</span>
<span class="c">path</span>
</pre></div>

<pre><code>## [1] "C:/Users/chanb/Documents/Repositories/Coursera/GettingAndCleaningData/Project"
</code></pre>

<h2>
<a name="user-content-get-the-data" class="anchor" href="#get-the-data"><span class="octicon octicon-link"></span></a>Get the data</h2>

<p>Download the file. Put it in the <code>Data</code> folder. <strong>This was already done on 2014-04-11; save time and don't evaluate again.</strong></p>

<div class="highlight highlight-r"><pre><span class="c">url &lt;- "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"</span>
<span class="c">f &lt;- "Dataset.zip"</span>
<span class="c">if (!file.exists(path)) {</span>
<span class="c">    dir.create(path)</span>
<span class="c">}</span>
<span class="c">download.file(url, file.path(path, f))</span>
</pre></div>

<p>Unzip the file. <strong>This was already done on 2014-04-11; save time and don't evaluate again.</strong></p>

<div class="highlight highlight-r"><pre><span class="c">executable &lt;- file.path("C:", "Program Files (x86)", "7-Zip", "7z.exe")</span>
<span class="c">parameters &lt;- "x"</span>
<span class="c">cmd &lt;- paste(paste0("\"", executable, "\""), parameters, paste0("\"", file.path(path, </span>
<span class="c">    f), "\""))</span>
<span class="c">system(cmd)</span>
</pre></div>

<p>The archive put the files in a folder named <code>UCI HAR Dataset</code>. Set this folder as the input path. List the files here.</p>

<div class="highlight highlight-r"><pre><span class="c">pathIn &lt;- file.path(path, "UCI HAR Dataset")</span>
<span class="c">list.files(pathIn, recursive = TRUE)</span>
</pre></div>

<pre><code>##  [1] "activity_labels.txt"                         
##  [2] "features.txt"                                
##  [3] "features_info.txt"                           
##  [4] "README.txt"                                  
##  [5] "test/Inertial Signals/body_acc_x_test.txt"   
##  [6] "test/Inertial Signals/body_acc_y_test.txt"   
##  [7] "test/Inertial Signals/body_acc_z_test.txt"   
##  [8] "test/Inertial Signals/body_gyro_x_test.txt"  
##  [9] "test/Inertial Signals/body_gyro_y_test.txt"  
## [10] "test/Inertial Signals/body_gyro_z_test.txt"  
## [11] "test/Inertial Signals/total_acc_x_test.txt"  
## [12] "test/Inertial Signals/total_acc_y_test.txt"  
## [13] "test/Inertial Signals/total_acc_z_test.txt"  
## [14] "test/subject_test.txt"                       
## [15] "test/X_test.txt"                             
## [16] "test/y_test.txt"                             
## [17] "train/Inertial Signals/body_acc_x_train.txt" 
## [18] "train/Inertial Signals/body_acc_y_train.txt" 
## [19] "train/Inertial Signals/body_acc_z_train.txt" 
## [20] "train/Inertial Signals/body_gyro_x_train.txt"
## [21] "train/Inertial Signals/body_gyro_y_train.txt"
## [22] "train/Inertial Signals/body_gyro_z_train.txt"
## [23] "train/Inertial Signals/total_acc_x_train.txt"
## [24] "train/Inertial Signals/total_acc_y_train.txt"
## [25] "train/Inertial Signals/total_acc_z_train.txt"
## [26] "train/subject_train.txt"                     
## [27] "train/X_train.txt"                           
## [28] "train/y_train.txt"
</code></pre>

<p><strong>See the <code>README.txt</code> file in C:/Users/chanb/Documents/Repositories/Coursera/GettingAndCleaningData/Project for detailed information on the dataset.</strong></p>

<p>For the purposes of this project, the files in the <code>Inertial Signals</code> folders are not used.</p>

<h2>
<a name="user-content-read-the-files" class="anchor" href="#read-the-files"><span class="octicon octicon-link"></span></a>Read the files</h2>

<p>Read the subject files.</p>

<div class="highlight highlight-r"><pre><span class="c">dtSubjectTrain &lt;- fread(file.path(pathIn, "train", "subject_train.txt"))</span>
<span class="c">dtSubjectTest &lt;- fread(file.path(pathIn, "test", "subject_test.txt"))</span>
</pre></div>

<p>Read the activity files. For some reason, these are called <em>label</em> files in the <code>README.txt</code> documentation.</p>

<div class="highlight highlight-r"><pre><span class="c">dtActivityTrain &lt;- fread(file.path(pathIn, "train", "Y_train.txt"))</span>
<span class="c">dtActivityTest &lt;- fread(file.path(pathIn, "test", "Y_test.txt"))</span>
</pre></div>

<p>Read the data files. <code>fread</code> seems to be giving me some trouble reading files. Using a helper function, read the file with <code>read.table</code> instead, then convert the resulting data frame to a data table. Return the data table.</p>

<div class="highlight highlight-r"><pre><span class="c">fileToDataTable &lt;- function(f) {</span>
<span class="c">    df &lt;- read.table(f)</span>
<span class="c">    dt &lt;- data.table(df)</span>
<span class="c">}</span>
<span class="c">dtTrain &lt;- fileToDataTable(file.path(pathIn, "train", "X_train.txt"))</span>
<span class="c">dtTest &lt;- fileToDataTable(file.path(pathIn, "test", "X_test.txt"))</span>
</pre></div>

<h2>
<a name="user-content-merge-the-training-and-the-test-sets" class="anchor" href="#merge-the-training-and-the-test-sets"><span class="octicon octicon-link"></span></a>Merge the training and the test sets</h2>

<p>Concatenate the data tables.</p>

<div class="highlight highlight-r"><pre><span class="c">dtSubject &lt;- rbind(dtSubjectTrain, dtSubjectTest)</span>
<span class="c">setnames(dtSubject, "V1", "subject")</span>
<span class="c">dtActivity &lt;- rbind(dtActivityTrain, dtActivityTest)</span>
<span class="c">setnames(dtActivity, "V1", "activityNum")</span>
<span class="c">dt &lt;- rbind(dtTrain, dtTest)</span>
</pre></div>

<p>Merge columns.</p>

<div class="highlight highlight-r"><pre><span class="c">dtSubject &lt;- cbind(dtSubject, dtActivity)</span>
<span class="c">dt &lt;- cbind(dtSubject, dt)</span>
</pre></div>

<p>Set key.</p>

<div class="highlight highlight-r"><pre><span class="c">setkey(dt, subject, activityNum)</span>
</pre></div>

<h2>
<a name="user-content-extract-only-the-mean-and-standard-deviation" class="anchor" href="#extract-only-the-mean-and-standard-deviation"><span class="octicon octicon-link"></span></a>Extract only the mean and standard deviation</h2>

<p>Read the <code>features.txt</code> file. This tells which variables in <code>dt</code> are measurements for the mean and standard deviation.</p>

<div class="highlight highlight-r"><pre><span class="c">dtFeatures &lt;- fread(file.path(pathIn, "features.txt"))</span>
<span class="c">setnames(dtFeatures, names(dtFeatures), c("featureNum", "featureName"))</span>
</pre></div>

<p>Subset only measurements for the mean and standard deviation.</p>

<div class="highlight highlight-r"><pre><span class="c">dtFeatures &lt;- dtFeatures[grepl("mean\\(\\)|std\\(\\)", featureName)]</span>
</pre></div>

<p>Convert the column numbers to a vector of variable names matching columns in <code>dt</code>.</p>

<div class="highlight highlight-r"><pre><span class="c">dtFeatures$featureCode &lt;- dtFeatures[, paste0("V", featureNum)]</span>
<span class="c">head(dtFeatures)</span>
</pre></div>

<pre><code>##    featureNum       featureName featureCode
## 1:          1 tBodyAcc-mean()-X          V1
## 2:          2 tBodyAcc-mean()-Y          V2
## 3:          3 tBodyAcc-mean()-Z          V3
## 4:          4  tBodyAcc-std()-X          V4
## 5:          5  tBodyAcc-std()-Y          V5
## 6:          6  tBodyAcc-std()-Z          V6
</code></pre>

<div class="highlight highlight-r"><pre><span class="c">dtFeatures$featureCode</span>
</pre></div>

<pre><code>##  [1] "V1"   "V2"   "V3"   "V4"   "V5"   "V6"   "V41"  "V42"  "V43"  "V44" 
## [11] "V45"  "V46"  "V81"  "V82"  "V83"  "V84"  "V85"  "V86"  "V121" "V122"
## [21] "V123" "V124" "V125" "V126" "V161" "V162" "V163" "V164" "V165" "V166"
## [31] "V201" "V202" "V214" "V215" "V227" "V228" "V240" "V241" "V253" "V254"
## [41] "V266" "V267" "V268" "V269" "V270" "V271" "V345" "V346" "V347" "V348"
## [51] "V349" "V350" "V424" "V425" "V426" "V427" "V428" "V429" "V503" "V504"
## [61] "V516" "V517" "V529" "V530" "V542" "V543"
</code></pre>

<p>Subset these variables using variable names.</p>

<div class="highlight highlight-r"><pre><span class="c">select &lt;- c(key(dt), dtFeatures$featureCode)</span>
<span class="c">dt &lt;- dt[, select, with = FALSE]</span>
</pre></div>

<h2>
<a name="user-content-use-descriptive-activity-names" class="anchor" href="#use-descriptive-activity-names"><span class="octicon octicon-link"></span></a>Use descriptive activity names</h2>

<p>Read <code>activity_labels.txt</code> file. This will be used to add descriptive names to the activities.</p>

<div class="highlight highlight-r"><pre><span class="c">dtActivityNames &lt;- fread(file.path(pathIn, "activity_labels.txt"))</span>
<span class="c">setnames(dtActivityNames, names(dtActivityNames), c("activityNum", "activityName"))</span>
</pre></div>

<h2>
<a name="user-content-label-with-descriptive-activity-names" class="anchor" href="#label-with-descriptive-activity-names"><span class="octicon octicon-link"></span></a>Label with descriptive activity names</h2>

<p>Merge activity labels.</p>

<div class="highlight highlight-r"><pre><span class="c">dt &lt;- merge(dt, dtActivityNames, by = "activityNum", all.x = TRUE)</span>
</pre></div>

<p>Add <code>activityName</code> as a key.</p>

<div class="highlight highlight-r"><pre><span class="c">setkey(dt, subject, activityNum, activityName)</span>
</pre></div>

<p>Melt the data table to reshape it from a short and wide format to a tall and narrow format.</p>

<div class="highlight highlight-r"><pre><span class="c">dt &lt;- data.table(melt(dt, key(dt), variable.name = "featureCode"))</span>
</pre></div>

<p>Merge activity name.</p>

<div class="highlight highlight-r"><pre><span class="c">dt &lt;- merge(dt, dtFeatures[, list(featureNum, featureCode, featureName)], by = "featureCode", </span>
<span class="c">    all.x = TRUE)</span>
</pre></div>

<p>Create a new variable, <code>activity</code> that is equivalent to <code>activityName</code> as a factor class.
Create a new variable, <code>feature</code> that is equivalent to <code>featureName</code> as a factor class.</p>

<div class="highlight highlight-r"><pre><span class="c">dt$activity &lt;- factor(dt$activityName)</span>
<span class="c">dt$feature &lt;- factor(dt$featureName)</span>
</pre></div>

<p>Seperate features from <code>featureName</code> using the helper function <code>grepthis</code>.</p>

<div class="highlight highlight-r"><pre><span class="c">grepthis &lt;- function(regex) {</span>
<span class="c">    grepl(regex, dt$feature)</span>
<span class="c">}</span>
<span class="c">## Features with 2 categories</span>
<span class="c">n &lt;- 2</span>
<span class="c">y &lt;- matrix(seq(1, n), nrow = n)</span>
<span class="c">x &lt;- matrix(c(grepthis("^t"), grepthis("^f")), ncol = nrow(y))</span>
<span class="c">dt$featDomain &lt;- factor(x %*% y, labels = c("Time", "Freq"))</span>
<span class="c">x &lt;- matrix(c(grepthis("Acc"), grepthis("Gyro")), ncol = nrow(y))</span>
<span class="c">dt$featInstrument &lt;- factor(x %*% y, labels = c("Accelerometer", "Gyroscope"))</span>
<span class="c">x &lt;- matrix(c(grepthis("BodyAcc"), grepthis("GravityAcc")), ncol = nrow(y))</span>
<span class="c">dt$featAcceleration &lt;- factor(x %*% y, labels = c(NA, "Body", "Gravity"))</span>
<span class="c">x &lt;- matrix(c(grepthis("mean()"), grepthis("std()")), ncol = nrow(y))</span>
<span class="c">dt$featVariable &lt;- factor(x %*% y, labels = c("Mean", "SD"))</span>
<span class="c">## Features with 1 category</span>
<span class="c">dt$featJerk &lt;- factor(grepthis("Jerk"), labels = c(NA, "Jerk"))</span>
<span class="c">dt$featMagnitude &lt;- factor(grepthis("Mag"), labels = c(NA, "Magnitude"))</span>
<span class="c">## Features with 3 categories</span>
<span class="c">n &lt;- 3</span>
<span class="c">y &lt;- matrix(seq(1, n), nrow = n)</span>
<span class="c">x &lt;- matrix(c(grepthis("-X"), grepthis("-Y"), grepthis("-Z")), ncol = nrow(y))</span>
<span class="c">dt$featAxis &lt;- factor(x %*% y, labels = c(NA, "X", "Y", "Z"))</span>
</pre></div>

<p>Check to make sure all possible combinations of <code>feature</code> are accounted for by all possible combinations of the factor class variables.</p>

<div class="highlight highlight-r"><pre><span class="c">r1 &lt;- nrow(dt[, .N, by = c("feature")])</span>
<span class="c">r2 &lt;- nrow(dt[, .N, by = c("featDomain", "featAcceleration", "featInstrument", </span>
<span class="c">    "featJerk", "featMagnitude", "featVariable", "featAxis")])</span>
<span class="c">r1 == r2</span>
</pre></div>

<pre><code>## [1] TRUE
</code></pre>

<p>Yes, I accounted for all possible combinations. <code>feature</code> is now redundant.</p>

<h2>
<a name="user-content-create-a-tidy-data-set" class="anchor" href="#create-a-tidy-data-set"><span class="octicon octicon-link"></span></a>Create a tidy data set</h2>

<p>Create a data set with the average of each variable for each activity and each subject.</p>

<div class="highlight highlight-r"><pre><span class="c">setkey(dt, subject, activity, featDomain, featAcceleration, featInstrument, </span>
<span class="c">    featJerk, featMagnitude, featVariable, featAxis)</span>
<span class="c">dtTidy &lt;- dt[, list(count = .N, average = mean(value)), by = key(dt)]</span>
</pre></div>

<p>Make codebook.</p>

<div class="highlight highlight-r"><pre><span class="c">knit("makeCodebook.Rmd", output = "codebook.md", encoding = "ISO8859-1", quiet = TRUE)</span>
</pre></div>

<pre><code>## [1] "codebook.md"
</code></pre>

<div class="highlight highlight-r"><pre><span class="c">markdownToHTML("codebook.md", "codebook.html")</span>
</pre></div></article>
  </div>

  </div>
</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" class="js-jump-to-line" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" class="js-jump-to-line-form">
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="button">Go</button>
  </form>
</div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer">
    <ul class="site-footer-links right">
      <li><a href="https://status.github.com/">Status</a></li>
      <li><a href="http://developer.github.com">API</a></li>
      <li><a href="http://training.github.com">Training</a></li>
      <li><a href="http://shop.github.com">Shop</a></li>
      <li><a href="/blog">Blog</a></li>
      <li><a href="/about">About</a></li>

    </ul>

    <a href="/">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
    </a>

    <ul class="site-footer-links">
      <li>&copy; 2014 <span title="0.05249s from github-fe118-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="/site/terms">Terms</a></li>
        <li><a href="/site/privacy">Privacy</a></li>
        <li><a href="/security">Security</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
  </div><!-- /.site-footer -->
</div><!-- /.container -->


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-fullscreen-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder="" data-suggester="fullscreen_suggester"></textarea>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x close js-ajax-error-dismiss"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-c044173f1e759e8299dbe414ec8ed23e4405bdc5.js" type="text/javascript"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-29f58289d332be6793882fd0aa758ff78c310289.js" type="text/javascript"></script>
      
      
        <script async src="https://www.google-analytics.com/analytics.js"></script>
  </body>
</html>

