<pre>
████████ ██   ██ ██ ██████   █████  ██    ██ ██      ████████
   ██    ██   ██ ██ ██   ██ ██   ██ ██    ██ ██         ██
   ██    ███████ ██ ██████  ███████ ██    ██ ██         ██
   ██    ██   ██ ██ ██   ██ ██   ██ ██    ██ ██         ██
   ██    ██   ██ ██ ██████  ██   ██  ██████  ███████    ██
</pre>

<pre>
             ▄████████▄     <b>thibault</b>@<b>theodo</b>
             ██▄████████    ───────────────────────────────────────────
             ███████████    <b>role</b>      tech lead @ <a href="https://github.com/theodo-group">theodo</a>, paris
             ██████▄▄▄▄     <b>work</b>      product teams, mostly healthcare
  █         ██████          <b>stack</b>     typescript · nestjs · react · postgres
  ██▄    ▄█████████▄▄       <b>also</b>      go · rust · python · php · ruby
  ███████████████  ▀        <b>agents</b>    claude code · pi · codex · opencode · openclaw
   ▀███████████             <b>setup</b>     nvim · ghostty · herdr · starship · catppuccin
     ████▀▀███              <b>volunteer</b> <a href="https://pyronear.org">pyronear</a>, open-source wildfire detection
     ██▀    ██▄
</pre>

<pre>
<b>$</b> git log --since=2025-09 --format="%ad  %s" --date=short

2026-10  <b>feat(healthcare-software)</b>: building an AI-powered learning platform
         teaching 350+ devs, product managers and QAs to leverage agents
         tanstack start · react 19 · a cloud dev workstation per learner with code-oss and t3code

2026-04  <b>feat(hospital-staffing)</b>: ported a staff-planning product into an existing HR platform
         15 go microservices → 15 nestjs, ~500k lines. tech lead of one of two squads;
         we shipped it through a claude code software factory the team built

2026-04  <b>feat(health-data)</b>: MVP of a lab data portal, built from scratch in 9 days
         react 19 · hono · keycloak sso · embedded metabase, access by subscription tier

2025-12  <b>feat(spirits-group)</b>: rewrote an A&amp;P budgeting platform
         express/oracle/angularjs → nestjs/prostgres/react, with approval engine and Excel imports

2025-09  <b>feat(medtech)</b>: french health-system integrations for a neurology platform
         INSi national patient identity, DMP access, compliant patient search. symfony
</pre>

Note: a lot of my work lives on client GitLabs and client GitHub orgs. I replay each commit's timestamp
(dates only, no code) into a ledger repo, so it still shows in the contribution graph.

<pre>
<b>$</b> tree ~/code -L 2

~/code
├── <b>oss/</b>
│   ├── <a href="https://github.com/pyronear/new-pyro-platform">pyronear</a>              alerts dashboard + api; leading the move to keycloak sso
│   └── <a href="https://github.com/typeorm/typeorm/pull/11119">typeorm</a>               fix createPropertyPath on *-to-many relations (merged)
├── <b>pi-extensions/</b>
│   ├── <a href="https://github.com/ThbltLmr/pi-modal-editor">pi-modal-editor</a>       vim modal editing for the pi prompt
│   ├── <a href="https://github.com/ThbltLmr/pi-btw">pi-btw</a>                /btw side questions that never touch the agent's context
│   ├── <a href="https://github.com/ThbltLmr/pi-stash">pi-stash</a>              ctrl+s prompt stash, keeps cursor, pastes and vim state
│   └── <a href="https://github.com/ThbltLmr/pi-starship-footer">pi-starship-footer</a>    starship-style footer: context, model, git, quota, cost
└── <b>toys/</b>
    ├── <a href="https://github.com/ThbltLmr/yt-term">yt-term</a>               youtube live, rendered in your terminal (rust, kitty graphics)
    ├── <a href="https://github.com/ThbltLmr/claudinosaur">claudinosaur</a>          chrome dino game while claude code thinks (claude code mod, typescript)
    ├── <a href="https://github.com/ThbltLmr/herdr-omarchy-widget">herdr-omarchy-widget</a>  agent status in the omarchy bar, click to focus
</pre>
