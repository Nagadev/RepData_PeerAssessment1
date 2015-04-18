


<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>RepData_PeerAssessment1/PA1_template.md at master · AnaLira/RepData_PeerAssessment1</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="AnaLira/RepData_PeerAssessment1" name="twitter:title" /><meta content="RepData_PeerAssessment1 - Reproducible Research Assignment1" name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/9981836?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/9981836?v=3&amp;s=400" property="og:image" /><meta content="AnaLira/RepData_PeerAssessment1" property="og:title" /><meta content="https://github.com/AnaLira/RepData_PeerAssessment1" property="og:url" /><meta content="RepData_PeerAssessment1 - Reproducible Research Assignment1" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTEzMDkwMjA6YTFiNWZlNGQ0MTFmZjY3MTc0YWE2OTViMGY4OTQ0YmE6MjNhMGYzZGEyOGExYmEyOWE5NmNlZWRjMjIxYjIxNzliYzFmZTA2ZDNlMDRkMDBmYTdiMGRlMGIzYmY5NTc4MA==--c3099a3c5f7d690a24e3f856e5f72da470e20eb1">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="01273FB7:1414:58D08C0:5531EDF4" name="octolytics-dimension-request_id" /><meta content="11309020" name="octolytics-actor-id" /><meta content="Nagadev" name="octolytics-actor-login" /><meta content="49b7b6af6475fa54dfe0d8b3268de0dcc6e9a4c08cf83f80f7d0ec1c5f4321ce" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged In">
    <meta class="js-ga-set" name="dimension2" content="Header v4">
    <meta name="is-dotcom" content="true">
    <meta name="hostname" content="github.com">
    <meta name="user-login" content="Nagadev">

    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="28nhGaagoHOIpOvt9ohTAG4cNcQgiNxIM4lC/aGd/TmyvwXSc74nGaxCGR0DmFhO1jPa2Xn+UzYrNoCkxMRQdw==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-99d0b872ee54fd3afae4675a7592394fa9d65696f8ad7a751b79704bc999f40a.css" media="all" rel="stylesheet" />
    <link href="https://assets-cdn.github.com/assets/github2-4dcecdbd59af4cd1dd8cf24ccaf35b686d848468ddcd7d52a8bf57c21ac4e5fb.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="f16199bf45edde13bbc8d0c453f279fe">

      
  <meta name="description" content="RepData_PeerAssessment1 - Reproducible Research Assignment1">
  <meta name="go-import" content="github.com/AnaLira/RepData_PeerAssessment1 git https://github.com/AnaLira/RepData_PeerAssessment1.git">

  <meta content="9981836" name="octolytics-dimension-user_id" /><meta content="AnaLira" name="octolytics-dimension-user_login" /><meta content="34081284" name="octolytics-dimension-repository_id" /><meta content="AnaLira/RepData_PeerAssessment1" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="34081284" name="octolytics-dimension-repository_network_root_id" /><meta content="AnaLira/RepData_PeerAssessment1" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/AnaLira/RepData_PeerAssessment1/commits/master.atom" rel="alternate" title="Recent Commits to RepData_PeerAssessment1:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      


        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/AnaLira/RepData_PeerAssessment1/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/AnaLira/RepData_PeerAssessment1/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <input type="text"
    class="js-site-search-field is-clearable"
    data-hotkey="s"
    name="q"
    placeholder="Search"
    data-global-scope-placeholder="Search GitHub"
    data-repo-scope-placeholder="Search"
    tabindex="1"
    autocapitalize="off">
  <div class="scope-badge">This repository</div>
</form>
      </div>

      <ul class="header-nav left" role="navigation">
          <li class="header-nav-item">
            <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="New header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
              Pull requests
</a>          </li>
          <li class="header-nav-item">
            <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="New header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
              Issues
</a>          </li>
            <li class="header-nav-item">
              <a class="header-nav-link" href="https://gist.github.com" data-ga-click="New header, go to gist, text:gist">Gist</a>
            </li>
      </ul>

      
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span 
        data-channel="notification-changed:Nagadev"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-inbox"></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new..."
       data-ga-click="New header, create new, icon:add">
      <span class="octicon octicon-plus left"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<li>
  <a href="/new" data-ga-click="Header, create new repository, icon:repo"><span class="octicon octicon-repo"></span> New repository</a>
</li>
<li>
  <a href="/organizations/new" data-ga-click="Header, create new organization, icon:organization"><span class="octicon octicon-organization"></span> New organization</a>
</li>


  <li class="dropdown-divider"></li>
  <li class="dropdown-header">
    <span title="AnaLira/RepData_PeerAssessment1">This repository</span>
  </li>
    <li>
      <a href="/AnaLira/RepData_PeerAssessment1/issues/new" data-ga-click="Header, create new issue, icon:issue"><span class="octicon octicon-issue-opened"></span> New issue</a>
    </li>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-s js-menu-target" href="#"
       aria-label="View profile and more"
       data-ga-click="New header, show menu, icon:avatar">
      <img alt="@Nagadev" class="avatar" data-user="11309020" height="20" src="https://avatars0.githubusercontent.com/u/11309020?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        <li>
          <a href="/Nagadev" data-ga-click="New header, go to profile, text:view profile">
            <span class="octicon octicon-person"></span>
            View profile
          </a>
        </li>

        <li>
          <a href="/stars" data-ga-click="New header, go to starred repos, text:starred repositories">
            <span class="octicon octicon-star"></span>
            Starred repositories
          </a>
        </li>

        <li>
          <a href="/explore" data-ga-click="New header, go to explore, text:explore">
            <span class="octicon octicon-telescope"></span>
            Explore
          </a>
        </li>

        <li>
          <a href="https://help.github.com" data-ga-click="New header, go to help, text:help">
            <span class="octicon octicon-question"></span>
            Help
          </a>
        </li>

        <li class="dropdown-divider"></li>


        <li>
          <a href="/settings/profile" data-ga-click="New header, go to settings, icon:settings">
            <span class="octicon octicon-gear"></span>
            Settings
          </a>
        </li>

        <li>
          <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Pdxbk1I0JF8ryRYFNQY54JPR+CNhbfv1XIaZGhsjNiLuOTufyUQpcS4CjfAtAxwFieJK2jQlLhX6yI9E9gGzqw==" /></div>
            <button class="sign-out-button" data-ga-click="New header, sign out, icon:logout">
              <span class="octicon octicon-sign-out"></span>
              Sign out
            </button>
</form>        </li>
      </ul>
    </div>
  </li>
</ul>



    
  </div>
</div>

        

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        
<ul class="pagehead-actions">

  <li>
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="B4cmJH8BdOeVnkHv/dXcF0U62b/oZedMbSn/cTo83UYnBK+v3vzzNKOLtRyBpkqhNpvUCaYFZc75n8YZOH32aw==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="34081284" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/AnaLira/RepData_PeerAssessment1/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>
        <a class="social-count js-social-count" href="/AnaLira/RepData_PeerAssessment1/watchers">
          1
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
                    Stop ignoring
                  </span>
                </div>
              </div>

            </div>

          </div>
        </div>
      </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/AnaLira/RepData_PeerAssessment1/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="A4Ckr7Tgi8X0R8TtLZyLpV7f57RGGtKuASLXL4cuRR071DrI/vvNmAc08MUrJFxfkDSJZJhVQd/Af7VPIZk0XQ==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar AnaLira/RepData_PeerAssessment1"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/AnaLira/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/AnaLira/RepData_PeerAssessment1/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="qxVGjByQs5ckHGQin0EeKkZJXanP9w3vcd5r4LU9qTxRyPZlvNVY/cgqLoIBt+QwepPWaeD3SHlq1Df2XxhzcQ==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star AnaLira/RepData_PeerAssessment1"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/AnaLira/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>  </div>

  </li>

        <li>
          <form accept-charset="UTF-8" action="/AnaLira/RepData_PeerAssessment1/fork" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="HyiqawGXz4GcI0HjKMNtdhrCIfFY3dmzTzOucUluhzJhEAm544MTaw1iovQeuWVgvzBtBqT3jw09T+cHuz6/2g==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of AnaLira/RepData_PeerAssessment1 to your account"
                aria-label="Fork your own copy of AnaLira/RepData_PeerAssessment1 to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
            <a href="/AnaLira/RepData_PeerAssessment1/network" class="social-count">0</a>
</form>        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/AnaLira" class="url fn" itemprop="url" rel="author"><span itemprop="title">AnaLira</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/AnaLira/RepData_PeerAssessment1" class="js-current-repository" data-pjax="#js-repo-pjax-container">RepData_PeerAssessment1</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/AnaLira/RepData_PeerAssessment1/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/AnaLira/RepData_PeerAssessment1" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /AnaLira/RepData_PeerAssessment1">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/AnaLira/RepData_PeerAssessment1/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /AnaLira/RepData_PeerAssessment1/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/AnaLira/RepData_PeerAssessment1/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /AnaLira/RepData_PeerAssessment1/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/AnaLira/RepData_PeerAssessment1/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /AnaLira/RepData_PeerAssessment1/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/AnaLira/RepData_PeerAssessment1/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /AnaLira/RepData_PeerAssessment1/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/AnaLira/RepData_PeerAssessment1/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /AnaLira/RepData_PeerAssessment1/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/AnaLira/RepData_PeerAssessment1.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" data-copy-hint="Copy to clipboard" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:AnaLira/RepData_PeerAssessment1.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" data-copy-hint="Copy to clipboard" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/AnaLira/RepData_PeerAssessment1" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" data-copy-hint="Copy to clipboard" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<p class="clone-options">You can clone with
  <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>, <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>, or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>


  <a href="https://windows.github.com" class="btn btn-sm sidebar-button" title="Save AnaLira/RepData_PeerAssessment1 to your computer and use it in GitHub Desktop." aria-label="Save AnaLira/RepData_PeerAssessment1 to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>


                <a href="/AnaLira/RepData_PeerAssessment1/archive/master.zip"
                   class="btn btn-sm sidebar-button"
                   aria-label="Download the contents of AnaLira/RepData_PeerAssessment1 as a zip file"
                   title="Download the contents of AnaLira/RepData_PeerAssessment1 as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          

<a href="/AnaLira/RepData_PeerAssessment1/blob/e1f981cb97226e8b42d29cf7277e5c985ebb5c45/PA1_template.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:d242821d0f789a9243cfc81232eac398 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/AnaLira/RepData_PeerAssessment1/blob/master/PA1_template.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/AnaLira/RepData_PeerAssessment1/find/master"
          class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" data-copy-hint="Copy file path to clipboard" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/AnaLira/RepData_PeerAssessment1" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">RepData_PeerAssessment1</span></a></span></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="@AnaLira" class="avatar" data-user="9981836" height="24" src="https://avatars3.githubusercontent.com/u/9981836?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/AnaLira" rel="author">AnaLira</a></span>
        <time datetime="2015-04-17T19:26:35Z" is="relative-time">Apr 17, 2015</time>
        <div class="commit-title">
            <a href="/AnaLira/RepData_PeerAssessment1/commit/699a0ffebe209a5a43c57c80a9caaf036b33adee" class="message" data-pjax="true" title="Project1">Project1</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="@AnaLira" data-user="9981836" height="24" src="https://avatars3.githubusercontent.com/u/9981836?v=3&amp;s=48" width="24" />
            <a href="/AnaLira">AnaLira</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-actions">

      <div class="btn-group">
        <a href="/AnaLira/RepData_PeerAssessment1/raw/master/PA1_template.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/AnaLira/RepData_PeerAssessment1/blame/master/PA1_template.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/AnaLira/RepData_PeerAssessment1/commits/master/PA1_template.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="https://windows.github.com"
           aria-label="Open this file in GitHub for Windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <form accept-charset="UTF-8" action="/AnaLira/RepData_PeerAssessment1/edit/master/PA1_template.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="EMTA5nqL7SCpOsOsGZtyGshOk7qCxp29TXF8UKiMrfaMIGjtmOpA8iloqJlt53HL5piYsUPRlci8ZWQDsY/vcA==" /></div>
              <button class="octicon-btn tooltipped tooltipped-n" type="submit" aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <form accept-charset="UTF-8" action="/AnaLira/RepData_PeerAssessment1/delete/master/PA1_template.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="aabyZ+3wvxaThRelNIAKlp5d/TCn6DT1D5/QG3cXWvbduHF2RPrHqFVZEkgRXujlQ6MPjXzB9LF/75dtVeXCWg==" /></div>
            <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-n" type="submit" aria-label="Fork this project and delete this file" data-disable-with>
              <span class="octicon octicon-trashcan"></span>
            </button>
</form>    </div>

    <div class="file-info">
        137 lines (96 sloc)
        <span class="file-info-divider"></span>
      5.007 kb
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><hr>

<p>Title: "Assigment1 Reproducible Research"</p>

<h1></h1>

<div class="highlight highlight-r"><pre>library(<span class="pl-smi">ggplot2</span>)
library(<span class="pl-smi">plyr</span>)
<span class="pl-smi">d</span><span class="pl-k">&lt;-</span>read.csv(<span class="pl-s"><span class="pl-pds">"</span>Activity.csv<span class="pl-pds">"</span></span>)</pre></div>

<h4>
<a id="user-content-1-what-is-mean-total-number-of-steps-taken-per-day" class="anchor" href="#1-what-is-mean-total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>1) What is mean total number of steps taken per day?</h4>

<p>To plot the total numbers of steps per day, a subset is created first using the ddply function. Then the histogram is plotted using the qplot function.</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">s2</span><span class="pl-k">&lt;-</span>ddply(<span class="pl-smi">d</span>,.(<span class="pl-smi">date</span>),<span class="pl-smi">summarize</span>,<span class="pl-v">steps</span><span class="pl-k">=</span>sum(<span class="pl-smi">steps</span>,<span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>))

qplot(<span class="pl-v">x</span><span class="pl-k">=</span><span class="pl-smi">date</span>, <span class="pl-v">y</span><span class="pl-k">=</span><span class="pl-smi">steps</span>,<span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-smi">s2</span>, <span class="pl-v">geom</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>bar<span class="pl-pds">"</span></span>, <span class="pl-v">stat</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>identity<span class="pl-pds">"</span></span>, <span class="pl-v">position</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>dodge<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> theme(<span class="pl-v">text</span> <span class="pl-k">=</span> element_text(<span class="pl-v">size</span><span class="pl-k">=</span><span class="pl-c1">10</span>),                                               <span class="pl-v">axis.text.x</span> <span class="pl-k">=</span> element_text(<span class="pl-v">angle</span><span class="pl-k">=</span><span class="pl-c1">90</span>, <span class="pl-v">vjust</span><span class="pl-k">=</span><span class="pl-c1">1</span>))</pre></div>

<p><a href="/AnaLira/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-2-1.png" target="_blank"><img src="/AnaLira/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-2-1.png" alt="plot of chunk unnamed-chunk-2" style="max-width:100%;"></a> </p>

<p>And the mean and median are calculated using the same subset s2 and stored in the "Steps_mean" and "Steps_median" variables</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">Steps_mean</span><span class="pl-k">&lt;-</span>mean(<span class="pl-smi">s2</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)
<span class="pl-smi">Steps_median</span><span class="pl-k">&lt;-</span>median(<span class="pl-smi">s2</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)
print(paste(<span class="pl-s"><span class="pl-pds">"</span>Mean total number of steps taken per day:<span class="pl-pds">"</span></span>,<span class="pl-smi">Steps_mean</span>))</pre></div>

<pre><code>## [1] "Mean total number of steps taken per day: 9354.22950819672"
</code></pre>

<div class="highlight highlight-r"><pre>print(paste(<span class="pl-s"><span class="pl-pds">"</span>Median total number of steps taken per day:<span class="pl-pds">"</span></span>,<span class="pl-smi">Steps_median</span>))</pre></div>

<pre><code>## [1] "Median total number of steps taken per day: 10395"
</code></pre>

<h4>
<a id="user-content-2-what-is-the-average-daily-activity-pattern" class="anchor" href="#2-what-is-the-average-daily-activity-pattern" aria-hidden="true"><span class="octicon octicon-link"></span></a>2) What is the average daily activity pattern?</h4>

<p>The average per interval is calculated with ddply function and stored in a subset "stepsxint".
The subset is plotted with qplot, highlighting the point (interval) with the highest average of steps through the geom_text function.</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">stepsxint</span><span class="pl-k">&lt;-</span>ddply(<span class="pl-smi">d</span>,.(<span class="pl-smi">interval</span>),<span class="pl-smi">summarize</span>,<span class="pl-v">steps</span><span class="pl-k">=</span>mean(<span class="pl-smi">steps</span>,<span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>))
qplot(<span class="pl-v">x</span><span class="pl-k">=</span><span class="pl-smi">interval</span>, <span class="pl-v">y</span><span class="pl-k">=</span><span class="pl-smi">steps</span>, <span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-smi">stepsxint</span>, <span class="pl-v">geom</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>point<span class="pl-pds">"</span></span>, <span class="pl-v">stat</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>identity<span class="pl-pds">"</span></span>, <span class="pl-v">position</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>dodge<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> theme(<span class="pl-v">text</span> <span class="pl-k">=</span> element_text(<span class="pl-v">size</span><span class="pl-k">=</span><span class="pl-c1">10</span>))<span class="pl-k">+</span>geom_text(<span class="pl-v">data</span><span class="pl-k">=</span>subset(<span class="pl-smi">stepsxint</span>, <span class="pl-smi">steps</span><span class="pl-k">==</span>max(<span class="pl-smi">stepsxint</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)),aes(<span class="pl-smi">interval</span>,<span class="pl-smi">steps</span>,<span class="pl-v">label</span><span class="pl-k">=</span>paste(<span class="pl-s"><span class="pl-pds">"</span>Highest average interval:<span class="pl-pds">"</span></span>,<span class="pl-smi">interval</span>,<span class="pl-s"><span class="pl-pds">"</span>,<span class="pl-pds">"</span></span>,round(<span class="pl-smi">steps</span>,<span class="pl-v">digits</span><span class="pl-k">=</span><span class="pl-c1">3</span>),<span class="pl-s"><span class="pl-pds">"</span> steps<span class="pl-pds">"</span></span>)))</pre></div>

<pre><code>## ymax not defined: adjusting position using y instead
</code></pre>

<p><a href="/AnaLira/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-4-1.png" target="_blank"><img src="/AnaLira/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-4-1.png" alt="plot of chunk unnamed-chunk-4" style="max-width:100%;"></a> </p>

<h4>
<a id="user-content-3imputing-missing-values" class="anchor" href="#3imputing-missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>3)Imputing missing values</h4>

<p>To stablish the amount of missing values in the dataset, we subset the data by taking only the TRUE values of the is.na() function, and apply the nrow function to the result.</p>

<p>To replace the missing values with the corresponding interval mean, a merged subset "mi"  was created to add the value to be replaced as an additional column.
Then looping through the matrix, all NA values were replaced with the new column value.</p>

<div class="highlight highlight-r"><pre>nrow(<span class="pl-smi">m</span><span class="pl-k">&lt;-</span><span class="pl-smi">d</span>[is.na(<span class="pl-smi">d</span><span class="pl-k">$</span><span class="pl-smi">steps</span>),])</pre></div>

<pre><code>## [1] 2304
</code></pre>

<div class="highlight highlight-r"><pre><span class="pl-smi">mi</span><span class="pl-k">&lt;-</span>merge(<span class="pl-smi">d</span>,<span class="pl-smi">stepsxint</span>,<span class="pl-v">by.x</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>interval<span class="pl-pds">"</span></span>,<span class="pl-v">by.y</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>interval<span class="pl-pds">"</span></span>)
<span class="pl-k">for</span> (<span class="pl-smi">i</span> <span class="pl-k">in</span> seq_along(<span class="pl-smi">mi</span><span class="pl-k">$</span><span class="pl-smi">interval</span>))
{
 <span class="pl-k">if</span>(is.na(<span class="pl-smi">mi</span>[<span class="pl-smi">i</span>,<span class="pl-s"><span class="pl-pds">"</span>steps.x<span class="pl-pds">"</span></span>])) {<span class="pl-smi">mi</span>[<span class="pl-smi">i</span>,<span class="pl-s"><span class="pl-pds">"</span>steps.x<span class="pl-pds">"</span></span>]<span class="pl-k">&lt;-</span><span class="pl-smi">mi</span>[<span class="pl-smi">i</span>,<span class="pl-s"><span class="pl-pds">"</span>steps.y<span class="pl-pds">"</span></span>]} 
 <span class="pl-k">else</span>{<span class="pl-k">next</span>}
}
<span class="pl-smi">mi</span><span class="pl-k">$</span><span class="pl-smi">steps.y</span><span class="pl-k">&lt;-</span><span class="pl-c1">NULL</span>
colnames(<span class="pl-smi">mi</span>)[<span class="pl-c1">2</span>]<span class="pl-k">&lt;-</span><span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span></pre></div>

<p>With the new dataset that equal to the original but with filled NA values, the steps for plotting the total daily steps and calculating the mean and median are repeated.</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">mi2</span><span class="pl-k">&lt;-</span>ddply(<span class="pl-smi">mi</span>,.(<span class="pl-smi">date</span>),<span class="pl-smi">summarize</span>,<span class="pl-v">steps</span><span class="pl-k">=</span>sum(<span class="pl-smi">steps</span>,<span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>))

qplot(<span class="pl-v">x</span><span class="pl-k">=</span><span class="pl-smi">date</span>, <span class="pl-v">y</span><span class="pl-k">=</span><span class="pl-smi">steps</span>,<span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-smi">mi2</span>, <span class="pl-v">geom</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>bar<span class="pl-pds">"</span></span>, <span class="pl-v">stat</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>identity<span class="pl-pds">"</span></span>, <span class="pl-v">position</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>dodge<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> theme(<span class="pl-v">text</span> <span class="pl-k">=</span> element_text(<span class="pl-v">size</span><span class="pl-k">=</span><span class="pl-c1">10</span>),                                               <span class="pl-v">axis.text.x</span> <span class="pl-k">=</span> element_text(<span class="pl-v">angle</span><span class="pl-k">=</span><span class="pl-c1">90</span>, <span class="pl-v">vjust</span><span class="pl-k">=</span><span class="pl-c1">1</span>))</pre></div>

<p><a href="/AnaLira/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-6-1.png" target="_blank"><img src="/AnaLira/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-6-1.png" alt="plot of chunk unnamed-chunk-6" style="max-width:100%;"></a> </p>

<div class="highlight highlight-r"><pre><span class="pl-smi">Steps_mean2</span><span class="pl-k">&lt;-</span>mean(<span class="pl-smi">mi2</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)
<span class="pl-smi">Steps_median2</span><span class="pl-k">&lt;-</span>median(<span class="pl-smi">mi2</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)
print(paste(<span class="pl-s"><span class="pl-pds">"</span>Mean total number of steps taken per day:<span class="pl-pds">"</span></span>,<span class="pl-smi">Steps_mean2</span>))</pre></div>

<pre><code>## [1] "Mean total number of steps taken per day: 10766.1886792453"
</code></pre>

<div class="highlight highlight-r"><pre>print(paste(<span class="pl-s"><span class="pl-pds">"</span>Median total number of steps taken per day:<span class="pl-pds">"</span></span>,<span class="pl-smi">Steps_median2</span>))</pre></div>

<pre><code>## [1] "Median total number of steps taken per day: 10766.1886792453"
</code></pre>

<p>The impact of filling NA values was an increase in the average steps per day.  Now the median equals the average.</p>

<h4>
<a id="user-content-are-there-differences-in-activity-patterns-between-weekdays-and-weekends" class="anchor" href="#are-there-differences-in-activity-patterns-between-weekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>Are there differences in activity patterns between weekdays and weekends?</h4>

<p>The original subset d is extended by adding a new column with the number of the weekday (0-7).
Based on this new column, using the ifelse() function the factor variable "weekday" is created with to separate the data in two group: weekends for days 0 and 7 (Sat-Sun) and the rest as weekend.</p>

<p>Then a new aggregated subset "wd" with the average number of step by interval and weekday is created and plotted.</p>

<p>The plot is generated and splited using the facet parameter by the weekday factor variable.</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">d</span><span class="pl-k">$</span><span class="pl-smi">wday</span><span class="pl-k">&lt;-</span>as.POSIXlt(<span class="pl-smi">d</span><span class="pl-k">$</span><span class="pl-smi">date</span>)<span class="pl-k">$</span><span class="pl-smi">wday</span>
<span class="pl-smi">d</span><span class="pl-k">$</span><span class="pl-smi">weekday</span><span class="pl-k">&lt;-</span>ifelse((<span class="pl-smi">d</span><span class="pl-k">$</span><span class="pl-smi">wday</span><span class="pl-k">==</span><span class="pl-c1">0</span>)<span class="pl-k">|</span>(<span class="pl-smi">d</span><span class="pl-k">$</span><span class="pl-smi">wday</span><span class="pl-k">==</span><span class="pl-c1">7</span>),<span class="pl-s"><span class="pl-pds">"</span>weekend<span class="pl-pds">"</span></span>,<span class="pl-s"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>)
<span class="pl-smi">wd</span><span class="pl-k">&lt;-</span>ddply(<span class="pl-smi">d</span>,.(<span class="pl-smi">weekday</span>,<span class="pl-smi">interval</span>),<span class="pl-smi">summarize</span>,<span class="pl-v">steps</span><span class="pl-k">=</span>mean(<span class="pl-smi">steps</span>,<span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>))
<span class="pl-smi">wd</span><span class="pl-k">$</span><span class="pl-smi">weekday</span><span class="pl-k">&lt;-</span><span class="pl-k">factor</span>(<span class="pl-smi">wd</span><span class="pl-k">$</span><span class="pl-smi">weekday</span>,<span class="pl-v">levels</span><span class="pl-k">=</span>c(<span class="pl-s"><span class="pl-pds">"</span>weekend<span class="pl-pds">"</span></span>,<span class="pl-s"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>),<span class="pl-v">labels</span><span class="pl-k">=</span>c(<span class="pl-s"><span class="pl-pds">"</span>weekends<span class="pl-pds">"</span></span>,<span class="pl-s"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>))
qplot(<span class="pl-v">x</span><span class="pl-k">=</span><span class="pl-smi">interval</span>, <span class="pl-v">y</span><span class="pl-k">=</span><span class="pl-smi">steps</span>,<span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-smi">wd</span>, <span class="pl-v">geom</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>line<span class="pl-pds">"</span></span>,<span class="pl-v">facets</span><span class="pl-k">=</span><span class="pl-smi">weekday</span><span class="pl-k">~</span>.)</pre></div>

<p><a href="/AnaLira/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-7-1.png" target="_blank"><img src="/AnaLira/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-7-1.png" alt="plot of chunk unnamed-chunk-7" style="max-width:100%;"></a> 
Looking at the graphs we can see how on weekend the activity increases and is more evenly distributed, presenting several peaks accross the day, while on weekdays we see a single peak in the morning and less activity during the rest of the day.</p>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.04986s from github-fe132-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
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
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-2c8ae50712a47d2b83d740cb875d55cdbbb3fdbccf303951cc6b7e63731e0c38.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-29f1a3f7b7d09cac4ebdeb6f7c87beaaef3237771dd3902546393d943f1c5269.js"></script>
      
      

      <div class="js-socket-channel" data-channel="test:Nagadev"></div>

  </body>
</html>

