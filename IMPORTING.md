



<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled emoji-size-boost is-u2f-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-be4c6e0e479a2d4d0eb3159c8772b5bfc4aa39831cb28f5f92cc2e448d93eaa1.css" integrity="sha256-vkxuDkeaLU0OsxWch3K1v8SqOYMcso9fkswuRI2T6qE=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-03e3cb14da417dba2a8e605c8d216b7e8237015c00fe3bbf8a16683bfbfa7234.css" integrity="sha256-A+PLFNpBfboqjmBcjSFrfoI3AVwA/ju/ihZoO/v6cjQ=" media="all" rel="stylesheet" />
    
    
    
    

    <link as="script" href="https://assets-cdn.github.com/assets/frameworks-e473d5424fface697be40bd46eb877027b3ecdc58f266fed330b402413df30d5.js" rel="preload" />
    
    <link as="script" href="https://assets-cdn.github.com/assets/github-5a05539a2ab04f10abd2879546db58882d74e2789b0164a23ac4bfdb431a461f.js" rel="preload" />

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=device-width">
    
    <title>labuildings/IMPORTING.md at master · osmlab/labuildings</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/apple-touch-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/apple-touch-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon-180x180.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="https://avatars2.githubusercontent.com/u/3856374?v=3&amp;s=400" name="twitter:image:src" /><meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="osmlab/labuildings" name="twitter:title" /><meta content="labuildings - Los Angeles County building import" name="twitter:description" />
      <meta content="https://avatars2.githubusercontent.com/u/3856374?v=3&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="osmlab/labuildings" property="og:title" /><meta content="https://github.com/osmlab/labuildings" property="og:url" /><meta content="labuildings - Los Angeles County building import" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/NDg5Nzk5NzphN2RlNzViYWU0ZmZhZTYyZjM0N2Y0YjZlZTlmZDM1NjoxODNmNTNiMGZjYTM1ODVjOWE0Mzk5YzNjZTdmMDg5ODE4MGFkYTdjOTA2ODNkMjFmOWZmNjAzMWU2NGM1MTZm--5c89027a415d9825df05c37bbcd969166d0f758c">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">
    <meta name="request-id" content="6CB39657:32E3:2559343:57AE158A" data-pjax-transient>

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="6CB39657:32E3:2559343:57AE158A" name="octolytics-dimension-request_id" /><meta content="4897997" name="octolytics-actor-id" /><meta content="jesshami" name="octolytics-actor-login" /><meta content="4d6da3bf11a02d34b9613e559736322e91fd2edbf69fd9ab6d898f754d6f23f0" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />



  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="jesshami">

        <meta name="expected-hostname" content="github.com">
      <meta name="js-proxy-site-detection-payload" content="ZTNlZGQ2MDE5ZDY1NmM1YTY4ZmJlZjAwYzg4NWU5OWMxNTcwODAyMWI2OWJjNWQxZmEzMWQ0YWRhNzQxYzkxMXx7InJlbW90ZV9hZGRyZXNzIjoiMTA4LjE3OS4xNTAuODciLCJyZXF1ZXN0X2lkIjoiNkNCMzk2NTc6MzJFMzoyNTU5MzQzOjU3QUUxNThBIiwidGltZXN0YW1wIjoxNDcxMDI2NTcxfQ==">


      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta name="html-safe-nonce" content="a569f0942b3b3508f9651f8ee39c5319711eb90a">
    <meta content="5bf7fe1342b85a6c6067db73f52f257e59ceeeab" name="form-nonce" />

    <meta http-equiv="x-pjax-version" content="ea403cf11fb3a2c97e76c11d8cc4ee89">
    

      
  <meta name="description" content="labuildings - Los Angeles County building import">
  <meta name="go-import" content="github.com/osmlab/labuildings git https://github.com/osmlab/labuildings.git">

  <meta content="3856374" name="octolytics-dimension-user_id" /><meta content="osmlab" name="octolytics-dimension-user_login" /><meta content="24729665" name="octolytics-dimension-repository_id" /><meta content="osmlab/labuildings" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="24729665" name="octolytics-dimension-repository_network_root_id" /><meta content="osmlab/labuildings" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/osmlab/labuildings/commits/master.atom" rel="alternate" title="Recent Commits to labuildings:master" type="application/atom+xml">


      <link rel="canonical" href="https://github.com/osmlab/labuildings/blob/master/IMPORTING.md" data-pjax-transient>
  </head>


  <body class="logged-in  env-production macintosh vis-public page-blob">
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="28" version="1.1" viewBox="0 0 16 16" width="28"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>


        <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/osmlab/labuildings/search" class="js-site-search-form" data-scoped-search-url="/osmlab/labuildings/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
      <div class="header-search-scope">This repository</div>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
    </label>
</form></div>


      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
    
    <a href="/notifications" aria-label="You have unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s js-socket-channel js-notification-indicator" data-channel="tenant:1:notification-changed:4897997" data-ga-click="Header, go to notifications, icon:unread" data-hotkey="g n">
        <span class="mail-status unread"></span>
        <svg aria-hidden="true" class="octicon octicon-bell" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"></path></svg>
</a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <svg aria-hidden="true" class="octicon octicon-plus left" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"></path></svg>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="osmlab/labuildings">This repository</span>
  </div>
    <a class="dropdown-item" href="/osmlab/labuildings/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/jesshami"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@jesshami" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/4897997?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">jesshami</strong>
        </div>

        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/jesshami" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
          <a class="dropdown-item" href="/integrations" data-ga-click="Header, go to integrations, text:integrations">
            Integrations
          </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>


        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="5bf7fe1342b85a6c6067db73f52f257e59ceeeab" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="hwlJzkEdMmTtD4dDHtOWVgUe+zSTg/nPUf1yxMoqOgQsGMqfByADbQOI6JCi/s6YdBqlgktMb/L8gKLQculPrA==" /></div>
          <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>


      


    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="5bf7fe1342b85a6c6067db73f52f257e59ceeeab" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="p7fzldnqSizU8PebTCW8i2lsUWrl+MzbjZQZBj1UEcVnnGfcv7BeIXLx2+k/ImTwnhaZWd253H5D/5XG+12CVg==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="24729665" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/osmlab/labuildings/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
              Watch
            </span>
          </a>
          <a class="social-count js-social-count" href="/osmlab/labuildings/watchers">
            30
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
                      Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"></path></svg>
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

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/osmlab/labuildings/unstar" class="starred" data-form-nonce="5bf7fe1342b85a6c6067db73f52f257e59ceeeab" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="N17yu0T2DzQjnIfrXkTDfQ70yStCU984F9A3vIZ+J510jO+nyMUBd2lyDzCGHCPTVhskG4ySGVBniOnkCWz38w==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar osmlab/labuildings"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"></path></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/osmlab/labuildings/stargazers">
          30
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/osmlab/labuildings/star" class="unstarred" data-form-nonce="5bf7fe1342b85a6c6067db73f52f257e59ceeeab" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="XVOlGbeit9joLyVX29vx7cjnYYHM7pweuK5uPHmofmF68qAcafjJs6NqH7vk1Z1Pxtzw4xWRPEwRgIxoOF0mLA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star osmlab/labuildings"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"></path></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/osmlab/labuildings/stargazers">
          30
        </a>
</form>  </div>

  </li>

  <li>
          <a href="#fork-destination-box" class="btn btn-sm btn-with-count"
              title="Fork your own copy of osmlab/labuildings to your account"
              aria-label="Fork your own copy of osmlab/labuildings to your account"
              rel="facebox"
              data-ga-click="Repository, show fork modal, action:blob#show; text:Fork">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg>
            Fork
          </a>

          <div id="fork-destination-box" style="display: none;">
            <h2 class="facebox-header" data-facebox-id="facebox-header">Where should we fork this repository?</h2>
            <include-fragment src=""
                class="js-fork-select-fragment fork-select-fragment"
                data-url="/osmlab/labuildings/fork?fragment=1">
              <img alt="Loading" height="64" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-128.gif" width="64" />
            </include-fragment>
          </div>

    <a href="/osmlab/labuildings/network" class="social-count">
      10
    </a>
  </li>
</ul>

    <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"></path></svg>
  <span class="author" itemprop="author"><a href="/osmlab" class="url fn" rel="author">osmlab</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/osmlab/labuildings" data-pjax="#js-repo-pjax-container">labuildings</a></strong>

</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/osmlab/labuildings" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /osmlab/labuildings" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"></path></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/osmlab/labuildings/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /osmlab/labuildings/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"></path></svg>
        <span itemprop="name">Issues</span>
        <span class="counter">20</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/osmlab/labuildings/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /osmlab/labuildings/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg>
      <span itemprop="name">Pull requests</span>
      <span class="counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/osmlab/labuildings/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /osmlab/labuildings/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"></path></svg>
      Wiki
</a>

  <a href="/osmlab/labuildings/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /osmlab/labuildings/pulse">
    <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0v2h3.6l.9-1.8.9 5.4L9 8.5l1.6 1.5H14V8z"></path></svg>
    Pulse
</a>
  <a href="/osmlab/labuildings/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /osmlab/labuildings/graphs">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"></path></svg>
    Graphs
</a>

</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/osmlab/labuildings/blob/16888324cd011667135ea5a63314ec8dec686b1d/IMPORTING.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:7df864a59ca8298ab24de818caf7c72e -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu branch-select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/osmlab/labuildings/blob/bldgusedata/IMPORTING.md"
               data-name="bldgusedata"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                bldgusedata
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/osmlab/labuildings/blob/master/IMPORTING.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
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
    <a href="/osmlab/labuildings/find/master"
          class="js-pjax-capture-input btn btn-sm"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/osmlab/labuildings"><span>labuildings</span></a></span></span><span class="separator">/</span><strong class="final-path">IMPORTING.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="right">
        <a class="commit-tease-sha" href="/osmlab/labuildings/commit/241f1c6466e00ff7a2045c55135f58705194c71e" data-pjax>
          241f1c6
        </a>
        <relative-time datetime="2016-07-27T15:32:03Z">Jul 27, 2016</relative-time>
      </span>
      <div>
        <img alt="@jschleuss" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/695934?v=3&amp;s=40" width="20" />
        <a href="/jschleuss" class="user-mention" rel="contributor">jschleuss</a>
          <a href="/osmlab/labuildings/commit/241f1c6466e00ff7a2045c55135f58705194c71e" class="message" data-pjax="true" title="easier to copy">easier to copy</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>8</strong>
         contributors
      </button>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="maning" href="/osmlab/labuildings/commits/master/IMPORTING.md?author=maning"><img alt="@maning" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/353700?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="almccon" href="/osmlab/labuildings/commits/master/IMPORTING.md?author=almccon"><img alt="@almccon" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/1212178?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="machikoyasuda" href="/osmlab/labuildings/commits/master/IMPORTING.md?author=machikoyasuda"><img alt="@machikoyasuda" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/3673236?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="jschleuss" href="/osmlab/labuildings/commits/master/IMPORTING.md?author=jschleuss"><img alt="@jschleuss" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/695934?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="meetar" href="/osmlab/labuildings/commits/master/IMPORTING.md?author=meetar"><img alt="@meetar" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/459970?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="planemad" href="/osmlab/labuildings/commits/master/IMPORTING.md?author=planemad"><img alt="@planemad" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/126868?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="michaelkirk" href="/osmlab/labuildings/commits/master/IMPORTING.md?author=michaelkirk"><img alt="@michaelkirk" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/217057?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="cityhubla" href="/osmlab/labuildings/commits/master/IMPORTING.md?author=cityhubla"><img alt="@cityhubla" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/6407796?v=3&amp;s=40" width="20" /> </a>


    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@maning" height="24" src="https://avatars3.githubusercontent.com/u/353700?v=3&amp;s=48" width="24" />
            <a href="/maning">maning</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@almccon" height="24" src="https://avatars0.githubusercontent.com/u/1212178?v=3&amp;s=48" width="24" />
            <a href="/almccon">almccon</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@machikoyasuda" height="24" src="https://avatars2.githubusercontent.com/u/3673236?v=3&amp;s=48" width="24" />
            <a href="/machikoyasuda">machikoyasuda</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jschleuss" height="24" src="https://avatars1.githubusercontent.com/u/695934?v=3&amp;s=48" width="24" />
            <a href="/jschleuss">jschleuss</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@meetar" height="24" src="https://avatars2.githubusercontent.com/u/459970?v=3&amp;s=48" width="24" />
            <a href="/meetar">meetar</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@planemad" height="24" src="https://avatars3.githubusercontent.com/u/126868?v=3&amp;s=48" width="24" />
            <a href="/planemad">planemad</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@michaelkirk" height="24" src="https://avatars2.githubusercontent.com/u/217057?v=3&amp;s=48" width="24" />
            <a href="/michaelkirk">michaelkirk</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@cityhubla" height="24" src="https://avatars3.githubusercontent.com/u/6407796?v=3&amp;s=48" width="24" />
            <a href="/cityhubla">cityhubla</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/osmlab/labuildings/raw/master/IMPORTING.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/osmlab/labuildings/blame/master/IMPORTING.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/osmlab/labuildings/commits/master/IMPORTING.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="github-mac://openRepo/https://github.com/osmlab/labuildings?branch=master&amp;filepath=IMPORTING.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:mac">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"></path></svg>
        </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/osmlab/labuildings/edit/master/IMPORTING.md" class="inline-form js-update-url-with-hash" data-form-nonce="5bf7fe1342b85a6c6067db73f52f257e59ceeeab" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="xmioy6DKjguKh1s8oObpHPuy2i+ZpIL3+S8qrrW2xF0/Sa1T284Zg3P2oPcIrBms0Eu6puN2w4f2U5vbsZ779Q==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"></path></svg>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/osmlab/labuildings/delete/master/IMPORTING.md" class="inline-form" data-form-nonce="5bf7fe1342b85a6c6067db73f52f257e59ceeeab" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="224fDPU0nfgZx4E+T+FgeBAt6+/ldXjn4lK9ArYcHXTnadVtrafrS22PuUYavmam1UkfzOQv+m0eHgEUTj4q+A==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"></path></svg>
          </button>
</form>  </div>

  <div class="file-info">
      166 lines (107 sloc)
      <span class="file-info-divider"></span>
    9.85 KB
  </div>
</div>

  
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-how-to-import" class="anchor" href="#how-to-import" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>How to import</h1>

<h2><a id="user-content-getting-started" class="anchor" href="#getting-started" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Getting started</h2>

<h3><a id="user-content-creating-an-import-account" class="anchor" href="#creating-an-import-account" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Creating an import account</h3>

<ul>
<li>OSM best practices require that you <a href="http://wiki.openstreetmap.org/wiki/Import/Guidelines#Use_a_dedicated_user_account">do not use your normal OSM account for the imports</a>. Create a new account for this purpose. 
Usually, it's your existing OSM username followed by <code>_imports</code> (e.g. <code>manings_imports or manings_labuilding)</code>.
Post your import account username in this <a href="http://github.com/osmlab/labuildings/issues/40">ticket</a>.</li>
</ul>

<h3><a id="user-content-getting-familiar-with-josm" class="anchor" href="#getting-familiar-with-josm" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Getting familiar with JOSM</h3>

<p>To contribute to this project, you need to use the JOSM editor.  Here are some resources to get you started:</p>

<ul>
<li>LearnOSM - <a href="http://learnosm.org/en/josm/">http://learnosm.org/en/josm/</a></li>
<li>Mapbox Mapping wiki - <a href="https://www.mapbox.com/blog/making-the-most-josm/">https://www.mapbox.com/blog/making-the-most-josm/</a></li>
</ul>

<h3><a id="user-content-check-out-a-task-on-the-tasking-manager" class="anchor" href="#check-out-a-task-on-the-tasking-manager" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Check out a task on the tasking manager</h3>

<ul>
<li>Tasks will be available on <strong><a href="http://labuildingsimport.com">http://labuildingsimport.com</a></strong>.</li>
<li>Priority: we are working on Los Angeles City first, which is broken down by census block groups. Each task performed is one block group within the city boundaries.</li>
<li>Why? Because different parts of the county have different data problems to watch out for. If we all run into the same problems at the same time, it will be easier for us to help each other and improve the processing scripts and the import workflow.</li>
</ul>

<h2><a id="user-content-import-workflow" class="anchor" href="#import-workflow" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Import workflow</h2>

<h3><a id="user-content-download-and-install-the-auto-tools-plugin" class="anchor" href="#download-and-install-the-auto-tools-plugin" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Download and install the auto-tools plugin</h3>

<ul>
<li>The good folks at Mapbox created a plugin to merge building shapes sliced by parcel boundaries. You can <a href="https://github.com/mapbox/auto-tools">find it here</a>. </li>
</ul>

<h3><a id="user-content-activating-josm-remote-control" class="anchor" href="#activating-josm-remote-control" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Activating JOSM Remote Control</h3>

<ul>
<li>Open JOSM and activate JOSM Remote Control. In the JOSM menu, for Windows, select <strong>Edit &gt; Preferences...</strong> or press <code>F12</code>. For Mac, select <strong>JOSM &gt; Preferences...</strong> or press, <code>⌘,</code>.</li>
<li>Click on the remote control icon.</li>
<li><p>Select <strong>Enable Remote Control</strong> and click <strong>OK</strong>.</p>

<p><a href="https://cloud.githubusercontent.com/assets/353700/13667682/adc1f10c-e6dd-11e5-8f01-e83a52460bfd.gif" target="_blank"><img src="https://cloud.githubusercontent.com/assets/353700/13667682/adc1f10c-e6dd-11e5-8f01-e83a52460bfd.gif" alt="josm_rc" style="max-width:100%;"></a></p></li>
</ul>

<h3><a id="user-content-adding-bing-imagery-background" class="anchor" href="#adding-bing-imagery-background" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Adding Bing imagery background</h3>

<ul>
<li>From the <strong>Imagery</strong> menu, select <strong>Bing aerial imagery</strong>.</li>
</ul>

<h3><a id="user-content-add-la-county-imagery-for-rural-areas" class="anchor" href="#add-la-county-imagery-for-rural-areas" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Add L.A. County imagery (for rural areas)</h3>

<ul>
<li><p>Bing's imagery outside of major cities can be as old as 2010 (and unusable on the islands). Add L.A. County's aerial tileserver with an offset: From <strong>Imagery</strong> select <strong>Imagery preferences</strong> and click on <strong>+ TMS</strong> and add the following URL: </p>

<p><code>http://cache.gis.lacounty.gov/cache/rest/services/LACounty_Cache/LACounty_Base/MapServer/tile/{zoom}/{y}/{x}</code><br></p>

<p><a href="https://cloud.githubusercontent.com/assets/695934/16742771/08ca96a4-475e-11e6-996a-4fff8232a5c9.gif" target="_blank"><img src="https://cloud.githubusercontent.com/assets/695934/16742771/08ca96a4-475e-11e6-996a-4fff8232a5c9.gif" alt="tile_server" style="max-width:100%;"></a></p></li>
</ul>

<h3><a id="user-content-selecting-a-task-in-the-tasking-manager" class="anchor" href="#selecting-a-task-in-the-tasking-manager" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Selecting a task in the Tasking Manager</h3>

<ul>
<li>Choose which area you want to work on from <strong><a href="http://labuildingsimport.com">http://labuildingsimport.com</a></strong> and click <strong>Start Mapping</strong>.</li>
<li>Download current data in OSM by clicking <strong>Edit in JOSM</strong>.</li>
</ul>

<p><a href="https://cloud.githubusercontent.com/assets/353700/14101327/6f8b279a-f5b1-11e5-83ef-b28d00afca62.gif" target="_blank"><img src="https://cloud.githubusercontent.com/assets/353700/14101327/6f8b279a-f5b1-11e5-83ef-b28d00afca62.gif" alt="download_osm" style="max-width:100%;"></a></p>

<ul>
<li><p>This will load the existing data from OpenStreetMap (<code>Data Layer 1</code>) and another background layer for the boundaries of the task (<code>Tasking Manager - #2</code>).  You will work only within the task boundary.</p></li>
<li><p>Get the <code>.osm</code> file you will import by clicking the link in the <strong>Extra Instructions</strong>.  This will download a new layer in JOSM.
At least two layers should be in JOSM: one with the imported data (<code>buildings-addresses####.osm</code>), one with current OSM data (<code>Data Layer 1</code>).</p>

<p><a href="https://cloud.githubusercontent.com/assets/353700/14101326/6f64d14e-f5b1-11e5-9748-8c56995a256d.gif" target="_blank"><img src="https://cloud.githubusercontent.com/assets/353700/14101326/6f64d14e-f5b1-11e5-9748-8c56995a256d.gif" alt="download_import" style="max-width:100%;"></a></p></li>
</ul>

<h3><a id="user-content-reviewing-the-data-before-uploading" class="anchor" href="#reviewing-the-data-before-uploading" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Reviewing the data before uploading</h3>

<ul>
<li>Review both data layers for possible conflicts.</li>
<li>Examine tags in both data sets to see if there are any conflicts.</li>
<li>If there are any problems you don't know how to deal with, do not proceed. Instead, flag the <code>.osm</code> file for a more advanced user to look at. 
(Use github <a href="http://github.com/osmlab/labuildings/issues">issues</a> to flag concerns, and/or create 
<a href="http://wiki.openstreetmap.org/wiki/Notes">OSM notes</a>). Then unlock your task on the tasking manager and pick a new area to work on.</li>
</ul>

<ul>
<li><p>Preserve the work of previous mappers wherever possible.  If existing buildings in OSM are of higher quality:</p>

<ul>
<li>Copy the tags from the import layer version.</li>
<li>Delete the building from the import layer.</li>
<li>Switch to the OSM layer.</li>
<li>Select the building, paste the tags.</li>
</ul></li>
<li><p>If the imported data are of higher quality, select both buildings and use the <strong>Replace geometry</strong> tool. </p>

<p><a href="https://cloud.githubusercontent.com/assets/353700/12942518/ddba87a4-d001-11e5-9441-2561f67b45bc.gif" target="_blank"><img src="https://cloud.githubusercontent.com/assets/353700/12942518/ddba87a4-d001-11e5-9441-2561f67b45bc.gif" alt="replace" style="max-width:100%;"></a> </p>

<ul>
<li> Run JOSM Validator, and if there are errors, fix them. </li>
</ul></li>
</ul>

<p><a href="https://cloud.githubusercontent.com/assets/353700/12942520/ddc572f4-d001-11e5-8cf6-399511cd47fa.gif" target="_blank"><img src="https://cloud.githubusercontent.com/assets/353700/12942520/ddc572f4-d001-11e5-8cf6-399511cd47fa.gif" alt="validator" style="max-width:100%;"></a> </p>

<h3><a id="user-content-finally-upload-it" class="anchor" href="#finally-upload-it" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Finally, upload it</h3>

<ul>
<li>Select both layers by shift-clicking them both.</li>
</ul>

<p><a href="https://cloud.githubusercontent.com/assets/3673236/14229615/ad4ea4ec-f8ec-11e5-8186-1980d0090ed9.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/3673236/14229615/ad4ea4ec-f8ec-11e5-8186-1980d0090ed9.png" alt="screen shot 2016-04-02 at 3 51 03 pm" style="max-width:100%;"></a></p>

<ul>
<li>Right-click the layers and click Merge.</li>
</ul>

<p><a href="https://cloud.githubusercontent.com/assets/3673236/14229616/ad4ebafe-f8ec-11e5-9ae0-444dcf540264.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/3673236/14229616/ad4ebafe-f8ec-11e5-9ae0-444dcf540264.png" alt="screen shot 2016-04-02 at 3 51 12 pm" style="max-width:100%;"></a></p>

<ul>
<li>Merge onto the <code>buildings-...osm</code> layer.</li>
</ul>

<p><a href="https://cloud.githubusercontent.com/assets/3673236/14229618/ad65cf96-f8ec-11e5-8d72-a6b661adedbd.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/3673236/14229618/ad65cf96-f8ec-11e5-8d72-a6b661adedbd.png" alt="screen shot 2016-04-02 at 3 51 21 pm" style="max-width:100%;"></a> </p>

<ul>
<li>Click the Upload button, the green up arrow button.</li>
</ul>

<p><a href="https://cloud.githubusercontent.com/assets/3673236/14229617/ad64e298-f8ec-11e5-9693-ba3f3a0e2085.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/3673236/14229617/ad64e298-f8ec-11e5-9693-ba3f3a0e2085.png" alt="screen shot 2016-04-02 at 3 53 02 pm" style="max-width:100%;"></a></p>

<ul>
<li>If you see a "Suspicious data found" warning, click "Continue upload"</li>
</ul>

<p><a href="https://cloud.githubusercontent.com/assets/3673236/14229619/ad72b6c0-f8ec-11e5-97b6-66b43f1c2937.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/3673236/14229619/ad72b6c0-f8ec-11e5-97b6-66b43f1c2937.png" alt="screen shot 2016-04-02 at 3 53 11 pm" style="max-width:100%;"></a></p>

<ul>
<li>Use the <strong>changeset comment</strong>: <code>LA County Building Import #labuildings https://wiki.openstreetmap.org/wiki/Los_angeles,_California/Buildings_Import</code> 
and <strong>source</strong>: <code>LA County GIS, http://egis3.lacounty.gov/dataportal/</code>.</li>
</ul>

<p><a href="https://cloud.githubusercontent.com/assets/3673236/14229620/ad73128c-f8ec-11e5-9e2f-44d272bd6403.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/3673236/14229620/ad73128c-f8ec-11e5-9e2f-44d272bd6403.png" alt="screen shot 2016-04-02 at 3 53 17 pm" style="max-width:100%;"></a></p>

<p>If you see an Authorization window asking you to log in to OpenStreetMap, log in and remember to use your <code>_import</code> username.</p>

<ul>
<li>Go back to the Tasking Manager and click <strong>Mark task as done</strong>.  Another mapper will validate your edits.</li>
</ul>

<h2><a id="user-content-what-to-watch-out-for" class="anchor" href="#what-to-watch-out-for" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>What to watch out for</h2>

<h3><a id="user-content-validate-the-import-with-your-eyes-before-uploading" class="anchor" href="#validate-the-import-with-your-eyes-before-uploading" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Validate the import with your eyes before uploading!</h3>

<ul>
<li>Run the <a href="http://wiki.openstreetmap.org/wiki/JOSM/Validator">JOSM validator</a>. Check for any errors it detects.</li>
<li><p>Check for small building parts that should be joined to the main building. We've already found a few examples of these in the data (see <a href="https://github.com/osmlab/labuildings/issues/19">issue #19</a>), so make sure you keep an eye out for these.  To join small parts, select both polygons and select <strong>Tools &gt; Join overlapping Area</strong>.</p>

<p><a href="https://cloud.githubusercontent.com/assets/695934/14264162/74ab59f4-fa73-11e5-8c4e-896c7fa2c2e4.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/695934/14264162/74ab59f4-fa73-11e5-8c4e-896c7fa2c2e4.png" alt="screen shot 2016-04-04 at 2 38 36 pm" style="max-width:100%;"></a></p></li>
</ul>

<p>If it's a small sliver, it makes sense that the "proper" data is on the larger object. Delete all the tags on the sliver and join the two objects.</p>

<p>If it's larger, like a strip mall split into pieces, then do:</p>

<ul>
<li><code>lacounty:ain</code> -&gt; ALL</li>
<li><code>lacount:bld_id</code> -&gt; ALL</li>
<li><code>start_date</code> -&gt; None if multiple or the one option if there's only one</li>
<li><code>height</code> -&gt; largest number</li>
<li><code>ele</code> -&gt; largest number </li>
<li><code>building:units</code> -&gt; none if different</li>
</ul>

<p><a href="https://cloud.githubusercontent.com/assets/695934/14264157/6c9f23ee-fa73-11e5-8744-e49d7e179003.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/695934/14264157/6c9f23ee-fa73-11e5-8744-e49d7e179003.png" alt="screen shot 2016-04-04 at 2 38 44 pm" style="max-width:100%;"></a></p>

<ul>
<li>Inspect everything else with a critical eye! Don't trust that the validator or FIXME tags will catch everything. There may be other bugs that only you can detect. Use your human smarts!</li>
</ul>

<h3><a id="user-content-conflating-with-existing-data" class="anchor" href="#conflating-with-existing-data" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Conflating with existing data</h3>

<ul>
<li>Look for any overlaps with existing buildings. Existing buildings in OSM are probably <em>more</em> up-to-date than our imported data. Do not assume the imported data is better, mostly likely it is worse! </li>
<li>Carefully combine the import data with the existing OSM data. If you aren't sure about some tags, ask someone! Especially ask the original mapper! </li>
</ul>

<h3><a id="user-content-how-to-ground-truth-the-data" class="anchor" href="#how-to-ground-truth-the-data" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>How to ground-truth the data</h3>

<ul>
<li>Up-to-date aerial imagery... try several sources.</li>
<li>See if the street is on <a href="http://www.mapillary.com/map/search/33.7585334163995/34.026616549869615/-118.72937986848933/-117.82764503425584">Mapillary</a>.</li>
<li>Go out and check it out yourself! Take a field trip!</li>
<li><strong>DO NOT USE GOOGLE MAPS OR GOOGLE STREET VIEW</strong>.</li>
</ul>

<h3><a id="user-content-identifying-new-buildings-with-imported-and-existing-data" class="anchor" href="#identifying-new-buildings-with-imported-and-existing-data" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Identifying new buildings with imported and existing data</h3>

<ul>
<li>The imagery from Bing was mostly from Los Angeles Region Image Acquisition Consortium (LARIAC).  This is the same imagery used as a reference for tracing the imported data.   In some areas, the imagery is more updated than the imported data and we can use it to identify newer buildings not found in the imported and existing data.</li>
<li>Newer building should be identified and flagged. Tag the building with <code>fixme</code> and add a note: <code>Appears in satelite imagery.</code>
<a href="https://cloud.githubusercontent.com/assets/3673236/14229396/ab9f392c-f8e7-11e5-80ca-635b97332bd8.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/3673236/14229396/ab9f392c-f8e7-11e5-80ca-635b97332bd8.png" alt="screen shot 2016-04-02 at 3 19 31 pm" style="max-width:100%;"></a></li>
<li>Likewise, buildings maybe demolished and does not exist anymore, delete them.</li>
</ul>

<h2><a id="user-content-communicate-communicate-communicate" class="anchor" href="#communicate-communicate-communicate" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Communicate communicate communicate!</h2>

<h3><a id="user-content-how-to-ask-for-help" class="anchor" href="#how-to-ask-for-help" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>How to ask for help</h3>

<ul>
<li>Create <a href="http://github.com/osmlab/labuildings/issues">issues</a> on this github repo.</li>
<li>Ask questions on the <a href="http://gitter.im/osmlab/labuildings">gitter channel</a>.</li>
<li>Contact <a href="http://twitter.com/mappingmashups">@mappingmashups</a>, <a href="https://twitter.com/theworksla">@theworksla</a>,  <a href="https://twitter.com/gaufre">@gaufre</a>,  <a href="http://twitter.com/maningsambale">@maningsambale</a>.</li>
</ul>

<h3><a id="user-content-how-to-share-your-progress" class="anchor" href="#how-to-share-your-progress" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>How to share your progress</h3>

<ul>
<li>Make sure you close your task on the tasking manager.</li>
</ul>

<h3><a id="user-content-how-to-communicate-with-other-mappers" class="anchor" href="#how-to-communicate-with-other-mappers" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>How to communicate with other mappers</h3>

<ul>
<li>JOSM <a href="http://wiki.openstreetmap.org/wiki/JOSM/Plugins/GeoChat">GeoChat</a> feature.</li>
<li>Twitter hashtag <code>#labuildings</code>.</li>
<li>Befriend other mappers on openstreetmap.com.</li>
</ul>
</article>
  </div>

</div>

<button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="hidden">Jump to Line</button>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>


    </div>
  </div>

    </div>

        <div class="container site-footer-container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage" class="site-footer-mark" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2016 <span title="0.07478s from github-fe154-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    

    <div id="ajax-error-message" class="ajax-error-message flash flash-error">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"></path></svg>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
      </button>
      You can't perform that action at this time.
    </div>


      
      <script crossorigin="anonymous" integrity="sha256-5HPVQk/6zml75AvUbrh3Ans+zcWPJm/tMwtAJBPfMNU=" src="https://assets-cdn.github.com/assets/frameworks-e473d5424fface697be40bd46eb877027b3ecdc58f266fed330b402413df30d5.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-WgVTmiqwTxCr0oeVRttYiC104nibAWSiOsS/20MaRh8=" src="https://assets-cdn.github.com/assets/github-5a05539a2ab04f10abd2879546db58882d74e2789b0164a23ac4bfdb431a461f.js"></script>
      
      
      
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"></path></svg>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
    <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
    </button>
  </div>
</div>

  </body>
</html>

