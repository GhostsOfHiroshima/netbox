# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav pt-0 pt-lg-4 ">
    <div class="repohead-details-container clearfix container-lg p-responsive d-none d-lg-block">

      <ul class="pagehead-actions">




  <li>
    
    <!-- '"` --><!-- </textarea></xmp> --><form class="clearfix js-social-form js-social-container" action="/notifications/subscribe" method="post" accept-charset="UTF-8" data-remote="true"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="/yvrU+o53fLXr+MdvreuAHk3dgcvxviSXXLc2BfYiZqtxAibIOEPtPRgS2k/qzxEerqId4HcgfeTPHlQq0tMGA==">      <input name="repository_id" type="hidden" value="194699860">

      <details class="details-reset details-overlay select-menu float-left">
        <summary tabindex="0" class="select-menu-button float-left btn btn-sm btn-with-count" role="button" aria-expanded="false" aria-haspopup="menu" data-ga-click="Repository, click Watch settings, action:blob#new" data-hydro-click-hmac="4e40b3aad694ecac018776d9d595824c9df366a74d3d12a77d1e09694e09c6df" data-hydro-click='{"event_type":"repository.click","payload":{"target":"WATCH_BUTTON","repository_id":194699860,"client_id":"1436831991.1561995148","originating_request_id":"F5C3:4CFA:F076:18D6F:5D1A280E","originating_url":"https://github.com/GhostsOfHiroshima/netbox/new/develop","referrer":"https://github.com/GhostsOfHiroshima/netbox/security/policy","user_id":51129449}}'>          <span data-menu-button="">
              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-eye v-align-text-bottom" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8.06 2 C 3 2 0 8 0 8 s 3 6 8.06 6 C 13 14 16 8 16 8 s -3 -6 -7.94 -6 Z M 8 12 c -2.2 0 -4 -1.78 -4 -4 c 0 -2.2 1.8 -4 4 -4 c 2.22 0 4 1.8 4 4 c 0 2.22 -1.78 4 -4 4 Z m 2 -4 c 0 1.11 -0.89 2 -2 2 c -1.11 0 -2 -0.89 -2 -2 c 0 -1.11 0.89 -2 2 -2 c 1.11 0 2 0.89 2 2 Z" /></svg>
              Watch
          </span>
</summary>        <details-menu class="select-menu-modal position-absolute mt-5" role="menu" style="z-index: 99;">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
          </div>
          <div class="select-menu-list">
            <button name="do" class="select-menu-item width-full" role="menuitemradio" aria-checked="true" type="submit" value="included">
              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Not watching</span>
                <span class="description">Be notified only when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents="">
                  <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-eye v-align-text-bottom" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8.06 2 C 3 2 0 8 0 8 s 3 6 8.06 6 C 13 14 16 8 16 8 s -3 -6 -7.94 -6 Z M 8 12 c -2.2 0 -4 -1.78 -4 -4 c 0 -2.2 1.8 -4 4 -4 c 2.22 0 4 1.8 4 4 c 0 2.22 -1.78 4 -4 4 Z m 2 -4 c 0 1.11 -0.89 2 -2 2 c -1.11 0 -2 -0.89 -2 -2 c 0 -1.11 0.89 -2 2 -2 c 1.11 0 2 0.89 2 2 Z" /></svg>
                  Watch
                </span>
              </div>
            </button>

            <button name="do" class="select-menu-item width-full" role="menuitemradio" aria-checked="false" type="submit" value="release_only">
              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Releases only</span>
                <span class="description">Be notified of new releases, and when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents="">
                  <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-eye v-align-text-bottom" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8.06 2 C 3 2 0 8 0 8 s 3 6 8.06 6 C 13 14 16 8 16 8 s -3 -6 -7.94 -6 Z M 8 12 c -2.2 0 -4 -1.78 -4 -4 c 0 -2.2 1.8 -4 4 -4 c 2.22 0 4 1.8 4 4 c 0 2.22 -1.78 4 -4 4 Z m 2 -4 c 0 1.11 -0.89 2 -2 2 c -1.11 0 -2 -0.89 -2 -2 c 0 -1.11 0.89 -2 2 -2 c 1.11 0 2 0.89 2 2 Z" /></svg>
                  Unwatch releases
                </span>
              </div>
            </button>

            <button name="do" class="select-menu-item width-full" role="menuitemradio" aria-checked="false" type="submit" value="subscribed">
              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Watching</span>
                <span class="description">Be notified of all conversations.</span>
                <span class="hidden-select-button-text" data-menu-button-contents="">
                  <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-eye v-align-text-bottom" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8.06 2 C 3 2 0 8 0 8 s 3 6 8.06 6 C 13 14 16 8 16 8 s -3 -6 -7.94 -6 Z M 8 12 c -2.2 0 -4 -1.78 -4 -4 c 0 -2.2 1.8 -4 4 -4 c 2.22 0 4 1.8 4 4 c 0 2.22 -1.78 4 -4 4 Z m 2 -4 c 0 1.11 -0.89 2 -2 2 c -1.11 0 -2 -0.89 -2 -2 c 0 -1.11 0.89 -2 2 -2 c 1.11 0 2 0.89 2 2 Z" /></svg>
                  Unwatch
                </span>
              </div>
            </button>

            <button name="do" class="select-menu-item width-full" role="menuitemradio" aria-checked="false" type="submit" value="ignore">
              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Ignoring</span>
                <span class="description">Never be notified.</span>
                <span class="hidden-select-button-text" data-menu-button-contents="">
                  <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-mute v-align-text-bottom" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8 2.81 v 10.38 c 0 0.67 -0.81 1 -1.28 0.53 L 3 10 H 1 c -0.55 0 -1 -0.45 -1 -1 V 7 c 0 -0.55 0.45 -1 1 -1 h 2 l 3.72 -3.72 C 7.19 1.81 8 2.14 8 2.81 Z m 7.53 3.22 l -1.06 -1.06 l -1.97 1.97 l -1.97 -1.97 l -1.06 1.06 L 11.44 8 L 9.47 9.97 l 1.06 1.06 l 1.97 -1.97 l 1.97 1.97 l 1.06 -1.06 L 13.56 8 l 1.97 -1.97 Z" /></svg>
                  Stop ignoring
                </span>
              </div>
            </button>
          </div>
        </details-menu>
      </details>
        <a class="social-count js-social-count" aria-label="0 users are watching this repository" href="/GhostsOfHiroshima/netbox/watchers">
          0
        </a>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --><form class="starred js-social-form" action="/GhostsOfHiroshima/netbox/unstar" method="post" accept-charset="UTF-8"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="LT3x3TYEjxvCq1B8LF2xXTO8wdupWkC6aa/spLRpKzYFWYSvi1fHitFjfjvj0EYYKGarTsolOmChqVcbQZX60w==">
      <input name="context" type="hidden" value="repository">
      <button title="Unstar GhostsOfHiroshima/netbox" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" type="submit" data-ga-click="Repository, click unstar button, action:blob#new; text:Unstar" data-hydro-click-hmac="3d7cb45f37a60f4f5481b375ab61173546a119822fff9b52a35cfa88e18c8d40" data-hydro-click='{"event_type":"repository.click","payload":{"target":"UNSTAR_BUTTON","repository_id":194699860,"client_id":"1436831991.1561995148","originating_request_id":"F5C3:4CFA:F076:18D6F:5D1A280E","originating_url":"https://github.com/GhostsOfHiroshima/netbox/new/develop","referrer":"https://github.com/GhostsOfHiroshima/netbox/security/policy","user_id":51129449}}'>        <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-star v-align-text-bottom" aria-hidden="true" viewBox="0 0 14 16" width="14" height="16" version="1.1"><path fill-rule="evenodd" d="M 14 6 l -4.9 -0.64 L 7 1 L 4.9 5.36 L 0 6 l 3.6 3.26 L 2.67 14 L 7 11.67 L 11.33 14 l -0.93 -4.74 L 14 6 Z" /></svg>
        Unstar
</button>        <a class="social-count js-social-count" aria-label="0 users starred this repository" href="/GhostsOfHiroshima/netbox/stargazers">
           0
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --><form class="unstarred js-social-form" action="/GhostsOfHiroshima/netbox/star" method="post" accept-charset="UTF-8"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="W4xuNH1rkk5AVeulwm13fPvBZQlPCIXYuf991RcmKksHorxQq1ZvO2BNEBYWlvnx9klTRj89qJAOxoa1ftglKA==">
      <input name="context" type="hidden" value="repository">
      <button title="Star GhostsOfHiroshima/netbox" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" type="submit" data-ga-click="Repository, click star button, action:blob#new; text:Star" data-hydro-click-hmac="0aabad494124977adc62700cf0bed8f003a0ca1ddab2c2d4220d68041933d595" data-hydro-click='{"event_type":"repository.click","payload":{"target":"STAR_BUTTON","repository_id":194699860,"client_id":"1436831991.1561995148","originating_request_id":"F5C3:4CFA:F076:18D6F:5D1A280E","originating_url":"https://github.com/GhostsOfHiroshima/netbox/new/develop","referrer":"https://github.com/GhostsOfHiroshima/netbox/security/policy","user_id":51129449}}'>        <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-star v-align-text-bottom" aria-hidden="true" viewBox="0 0 14 16" width="14" height="16" version="1.1"><path fill-rule="evenodd" d="M 14 6 l -4.9 -0.64 L 7 1 L 4.9 5.36 L 0 6 l 3.6 3.26 L 2.67 14 L 7 11.67 L 11.33 14 l -0.93 -4.74 L 14 6 Z" /></svg>
        Star
</button>        <a class="social-count js-social-count" aria-label="0 users starred this repository" href="/GhostsOfHiroshima/netbox/stargazers">
          0
        </a>
</form>  </div>

  </li>

  <li>
        <span class="btn btn-sm btn-with-count disabled tooltipped tooltipped-sw" aria-label="Cannot fork because you own this repository and are not a member of any organizations.">
          <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-repo-forked v-align-text-bottom" aria-hidden="true" viewBox="0 0 10 16" width="10" height="16" version="1.1"><path fill-rule="evenodd" d="M 8 1 a 1.993 1.993 0 0 0 -1 3.72 V 6 L 5 8 L 3 6 V 4.72 A 1.993 1.993 0 0 0 2 1 a 1.993 1.993 0 0 0 -1 3.72 V 6.5 l 3 3 v 1.78 A 1.993 1.993 0 0 0 5 15 a 1.993 1.993 0 0 0 1 -3.72 V 9.5 l 3 -3 V 4.72 A 1.993 1.993 0 0 0 8 1 Z M 2 4.2 C 1.34 4.2 0.8 3.65 0.8 3 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z m 3 10 c -0.66 0 -1.2 -0.55 -1.2 -1.2 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z m 3 -10 c -0.66 0 -1.2 -0.55 -1.2 -1.2 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z" /></svg>
          Fork
</span>
    <a class="social-count" aria-label="1016 users forked this repository" href="/GhostsOfHiroshima/netbox/network/members">
      1,016
    </a>
  </li>
</ul>

      <h1 class="public ">
    <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-repo-forked" aria-hidden="true" viewBox="0 0 10 16" width="10" height="16" version="1.1"><path fill-rule="evenodd" d="M 8 1 a 1.993 1.993 0 0 0 -1 3.72 V 6 L 5 8 L 3 6 V 4.72 A 1.993 1.993 0 0 0 2 1 a 1.993 1.993 0 0 0 -1 3.72 V 6.5 l 3 3 v 1.78 A 1.993 1.993 0 0 0 5 15 a 1.993 1.993 0 0 0 1 -3.72 V 9.5 l 3 -3 V 4.72 A 1.993 1.993 0 0 0 8 1 Z M 2 4.2 C 1.34 4.2 0.8 3.65 0.8 3 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z m 3 10 c -0.66 0 -1.2 -0.55 -1.2 -1.2 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z m 3 -10 c -0.66 0 -1.2 -0.55 -1.2 -1.2 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z" /></svg>
  <span class="author" itemprop="author"><a class="url fn" href="/GhostsOfHiroshima" rel="author" data-octo-dimensions="link_type:self" data-octo-click="hovercard-link-click" data-hovercard-url="/hovercards?user_id=51129449" data-hovercard-type="user">GhostsOfHiroshima</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/GhostsOfHiroshima/netbox" data-pjax="#js-repo-pjax-container">netbox</a></strong>
  

    <span class="fork-flag" data-repository-hovercards-enabled="">
      <span class="text">forked from <a href="/netbox-community/netbox" data-hovercard-url="/netbox-community/netbox/hovercard" data-hovercard-type="repository">netbox-community/netbox</a></span>
    </span>
</h1>

    </div>
    
<nav class="hx_reponav reponav js-repo-nav js-sidenav-container-pjax container-lg p-responsive d-none d-lg-block" aria-label="Repository" data-pjax="#js-repo-pjax-container" itemtype="http://schema.org/BreadcrumbList" itemscope="">

  <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
    <a class="js-selected-navigation-item selected reponav-item" aria-current="page" href="/GhostsOfHiroshima/netbox" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /GhostsOfHiroshima/netbox" itemprop="url">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-code" aria-hidden="true" viewBox="0 0 14 16" width="14" height="16" version="1.1"><path fill-rule="evenodd" d="M 9.5 3 L 8 4.5 L 11.5 8 L 8 11.5 L 9.5 13 L 14 8 L 9.5 3 Z m -5 0 L 0 8 l 4.5 5 L 6 11.5 L 2.5 8 L 6 4.5 L 4.5 3 Z" /></svg>
      <span itemprop="name">Code</span>
      <meta content="1" itemprop="position">
</a>  </span>


  <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
    <a class="js-selected-navigation-item reponav-item" href="/GhostsOfHiroshima/netbox/pulls" data-hotkey="g p" data-selected-links="repo_pulls checks /GhostsOfHiroshima/netbox/pulls" itemprop="url">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-git-pull-request" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 11 11.28 V 5 c -0.03 -0.78 -0.34 -1.47 -0.94 -2.06 C 9.46 2.35 8.78 2.03 8 2 H 7 V 0 L 4 3 l 3 3 V 4 h 1 c 0.27 0.02 0.48 0.11 0.69 0.31 c 0.21 0.2 0.3 0.42 0.31 0.69 v 6.28 A 1.993 1.993 0 0 0 10 15 a 1.993 1.993 0 0 0 1 -3.72 Z m -1 2.92 c -0.66 0 -1.2 -0.55 -1.2 -1.2 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z M 4 3 c 0 -1.11 -0.89 -2 -2 -2 a 1.993 1.993 0 0 0 -1 3.72 v 6.56 A 1.993 1.993 0 0 0 2 15 a 1.993 1.993 0 0 0 1 -3.72 V 4.72 c 0.59 -0.34 1 -0.98 1 -1.72 Z m -0.8 10 c 0 0.66 -0.55 1.2 -1.2 1.2 c -0.65 0 -1.2 -0.55 -1.2 -1.2 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 Z M 2 4.2 C 1.34 4.2 0.8 3.65 0.8 3 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z" /></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta content="3" itemprop="position">
</a>  </span>


    <a class="js-selected-navigation-item reponav-item" href="/GhostsOfHiroshima/netbox/projects" data-hotkey="g b" data-selected-links="repo_projects new_repo_project repo_project /GhostsOfHiroshima/netbox/projects">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-project" aria-hidden="true" viewBox="0 0 15 16" width="15" height="16" version="1.1"><path fill-rule="evenodd" d="M 10 12 h 3 V 2 h -3 v 10 Z m -4 -2 h 3 V 2 H 6 v 8 Z m -4 4 h 3 V 2 H 2 v 12 Z m -1 1 h 13 V 1 H 1 v 14 Z M 14 0 H 1 a 1 1 0 0 0 -1 1 v 14 a 1 1 0 0 0 1 1 h 13 a 1 1 0 0 0 1 -1 V 1 a 1 1 0 0 0 -1 -1 Z" /></svg>
      Projects
      <span class="Counter">0</span>
</a>

    <a class="js-selected-navigation-item reponav-item" href="/GhostsOfHiroshima/netbox/wiki" data-hotkey="g w" data-selected-links="repo_wiki /GhostsOfHiroshima/netbox/wiki">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-book" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 3 5 h 4 v 1 H 3 V 5 Z m 0 3 h 4 V 7 H 3 v 1 Z m 0 2 h 4 V 9 H 3 v 1 Z m 11 -5 h -4 v 1 h 4 V 5 Z m 0 2 h -4 v 1 h 4 V 7 Z m 0 2 h -4 v 1 h 4 V 9 Z m 2 -6 v 9 c 0 0.55 -0.45 1 -1 1 H 9.5 l -1 1 l -1 -1 H 2 c -0.55 0 -1 -0.45 -1 -1 V 3 c 0 -0.55 0.45 -1 1 -1 h 5.5 l 1 1 l 1 -1 H 15 c 0.55 0 1 0.45 1 1 Z m -8 0.5 L 7.5 3 H 2 v 9 h 6 V 3.5 Z m 7 -0.5 H 9.5 l -0.5 0.5 V 12 h 6 V 3 Z" /></svg>
      Wiki
</a>
    <a class="js-selected-navigation-item reponav-item" href="/GhostsOfHiroshima/netbox/network/alerts" data-selected-links="security alerts policy /GhostsOfHiroshima/netbox/network/alerts" data-skip-pjax="true">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-shield" aria-hidden="true" viewBox="0 0 14 16" width="14" height="16" version="1.1"><path fill-rule="evenodd" d="M 0 2 l 7 -2 l 7 2 v 6.02 C 14 12.69 8.69 16 7 16 c -1.69 0 -7 -3.31 -7 -7.98 V 2 Z m 1 0.75 L 7 1 l 6 1.75 v 5.268 C 13 12.104 8.449 15 7 15 c -1.449 0 -6 -2.896 -6 -6.982 V 2.75 Z m 1 0.75 L 7 2 v 12 c -1.207 0 -5 -2.482 -5 -5.985 V 3.5 Z" /></svg>
      Security
</a>
    <a class="js-selected-navigation-item reponav-item" href="/GhostsOfHiroshima/netbox/pulse" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people /GhostsOfHiroshima/netbox/pulse">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-graph" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 16 14 v 1 H 0 V 0 h 1 v 14 h 15 Z M 5 13 H 3 V 8 h 2 v 5 Z m 4 0 H 7 V 3 h 2 v 10 Z m 4 0 h -2 V 6 h 2 v 7 Z" /></svg>
      Insights
</a>
    <a class="js-selected-navigation-item reponav-item" href="/GhostsOfHiroshima/netbox/settings" data-selected-links="repo_settings repo_branch_settings hooks integration_installations repo_keys_settings issue_template_editor /GhostsOfHiroshima/netbox/settings">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-gear" aria-hidden="true" viewBox="0 0 14 16" width="14" height="16" version="1.1"><path fill-rule="evenodd" d="M 14 8.77 v -1.6 l -1.94 -0.64 l -0.45 -1.09 l 0.88 -1.84 l -1.13 -1.13 l -1.81 0.91 l -1.09 -0.45 l -0.69 -1.92 h -1.6 l -0.63 1.94 l -1.11 0.45 l -1.84 -0.88 l -1.13 1.13 l 0.91 1.81 l -0.45 1.09 L 0 7.23 v 1.59 l 1.94 0.64 l 0.45 1.09 l -0.88 1.84 l 1.13 1.13 l 1.81 -0.91 l 1.09 0.45 l 0.69 1.92 h 1.59 l 0.63 -1.94 l 1.11 -0.45 l 1.84 0.88 l 1.13 -1.13 l -0.92 -1.81 l 0.47 -1.09 L 14 8.75 v 0.02 Z M 7 11 c -1.66 0 -3 -1.34 -3 -3 s 1.34 -3 3 -3 s 3 1.34 3 3 s -1.34 3 -3 3 Z" /></svg>
      Settings
</a>
</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap" itemtype="http://schema.org/BreadcrumbList" itemscope="">

    <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
      <a class="js-selected-navigation-item selected reponav-item" aria-current="page" href="/GhostsOfHiroshima/netbox" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /GhostsOfHiroshima/netbox" itemprop="url">
        <span itemprop="name">Code</span>
        <meta content="1" itemprop="position">
</a>    </span>


    <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
      <a class="js-selected-navigation-item reponav-item" href="/GhostsOfHiroshima/netbox/pulls" data-selected-links="repo_pulls checks /GhostsOfHiroshima/netbox/pulls" itemprop="url">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">0</span>
        <meta content="3" itemprop="position">
</a>    </span>

      <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
        <a class="js-selected-navigation-item reponav-item" href="/GhostsOfHiroshima/netbox/projects" data-selected-links="repo_projects new_repo_project repo_project /GhostsOfHiroshima/netbox/projects" itemprop="url">
          <span itemprop="name">Projects</span>
          <span class="Counter">0</span>
          <meta content="4" itemprop="position">
</a>      </span>

      <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
        <a class="js-selected-navigation-item reponav-item" href="/GhostsOfHiroshima/netbox/wiki" data-selected-links="repo_wiki /GhostsOfHiroshima/netbox/wiki" itemprop="url">
          <span itemprop="name">Wiki</span>
          <meta content="5" itemprop="position">
</a>      </span>

      <a class="js-selected-navigation-item reponav-item" href="/GhostsOfHiroshima/netbox/network/alerts" data-selected-links="security alerts policy /GhostsOfHiroshima/netbox/network/alerts" itemprop="url">
        <span itemprop="name">Security</span>
        <meta content="6" itemprop="position">
</a>
      <a class="js-selected-navigation-item reponav-item" href="/GhostsOfHiroshima/netbox/pulse" data-selected-links="pulse /GhostsOfHiroshima/netbox/pulse">
        Pulse
</a>

  </nav>
</div>


  </div>
