---
layout: default
title: "About"
description: "A detailed profile of Naki / N4-K2 - developer, gamer, modder, mapper, storyteller, and worldbuilder."
permalink: /about/
---

{% include sections/page-hero.html eyebrow="PROFILE // ACTUAL HUMAN BEHIND THE DATABASE" title="About Me" description=page.description %}

<section class="section section-tight">
  <div class="shell profile-layout">
    <article class="glass-card prose" markdown="1">
      ## Hey, I'm Naki.

      Online I usually go by **Naki**, **N4-K2**, or **Nawkies** depending on what I'm doing. I'm a developer, gamer, modder, mapper, storyteller, worldbuilder, and the kind of person who can start with one small mechanic and somehow end up planning an entire progression system around it.

      A lot of my projects live where **code, game design, puzzles, and worldbuilding overlap**. I don't really enjoy making something that only has one layer if the idea clearly has room for more. If I'm building a map, I start thinking about secrets, traversal, collectibles, alternate routes, puzzles, progression, UI, achievements, lore, and tools for making the map easier to maintain. If I'm writing a character, I start thinking about their species, voice, relationships, visual rules, failure modes, timeline, and how they behave when the situation changes.

      ## The stuff I'm most into

      **Roblox and Linglox** are a huge part of what I make. I like designing enormous Linglox-style maps, prompt systems, themed zones, puzzle mechanics, traps, parkour, hidden areas, collectibles, and tools for moving map data between different workflows.

      **Minecraft Java Edition** is another major focus. I like modding, custom progression, advancement systems, educational gameplay, puzzle content, and turning ideas from other games into Minecraft mechanics without losing what made the original system interesting.

      I also spend a lot of time on **writing and worldbuilding**. My two biggest writing projects represented on this site are *TAHAUFYA: Found in the Noise* and *Casualties: Unknown - Broken Lives*. I like character-heavy stories with nonhuman species, complicated relationships, large casts, progression, continuity rules, and enough background information that the project eventually needs a proper wiki or character bible.

      Rhythm games and modding are part of the mix too. I like things around **Just Dance, Friday Night Funkin', osu!mania, music/chart timing, and game/mod experimentation**. I also enjoy poking at how games and mods work internally when I want to understand or recreate a system.

      ## How my projects usually grow

      I am extremely bad at letting a project stay tiny.

      A normal progression is something like: **idea -> mechanic -> more mechanics -> progression -> achievements -> secrets -> lore -> tooling -> "what else is missing?"**. That is how I end up with projects involving hundreds or thousands of prompts, huge advancement trees, large zone counts, detailed character databases, or way more configuration than the first version technically needed.

      I prefer **detail, customization, and systems that connect to each other**. I would rather have a mechanic interact with the rest of the project than exist as a disconnected gimmick.

      ## Coding / development

      Languages I use or experiment with include **Lua / Luau, Python, Java, JavaScript, C#, C++, and C**. For web work, this site also uses **HTML, CSS, Jekyll, and Liquid**.

      The exact language usually matters less to me than what I'm trying to build. I like programming when I can see the result doing something: spawning a game system, generating content, importing data, running a progression mechanic, organizing a wiki, or making a tool that removes repetitive work.

      ## Games and creative interests

      Some of the biggest recurring ones are **Minecraft Java Edition, Roblox, Linglox, Deltarune, Just Dance, rhythm games, puzzle games, game modding, progression systems, customization, and hidden mechanics**.

      Visually, I keep coming back to **cosmic, void, glitch, eldritch, dark-fantasy, digital, and neon aesthetics**, especially combinations of **black, deep purple, blue, crimson, and neon pink**. That's why this site looks more like a fictional database than a normal white portfolio page.

      ## Writing

      I like stories where characters have enough detail to remain recognizable outside of the immediate plot. That means I care about **voice, personality contradictions, relationships, species design, body language, continuity, emotional reactions, and how previous scenes actually change later behavior**.

      The TAHAUFYA section of this site now includes the full current-cast character bible rather than only short wiki summaries.

      ## Why this website is so big

      A tiny link page would be easier, but it would not really represent how I make things. This site is intentionally part **About Me**, part **portfolio**, part **project archive**, part **documentation site**, and part **fiction wiki**.

      In other words: if one page can reasonably become a database, there is a pretty good chance I will turn it into a database.
    </article>

    <aside class="profile-stack">
      <article class="glass-card">
        <div class="card-label">QUICK DATA</div>
        <dl class="data-list">
          <div><dt>Name</dt><dd>{{ site.data.profile.display_name }}</dd></div>
          <div><dt>Age</dt><dd>{{ site.data.profile.age }}</dd></div>
          <div><dt>Aliases</dt><dd>{{ site.data.profile.aliases | join: " / " }}</dd></div>
          <div><dt>Pronouns</dt><dd>{{ site.data.profile.pronouns }}</dd></div>
          <div><dt>Region</dt><dd>{{ site.data.profile.region }}</dd></div>
          <div><dt>Timezone</dt><dd>{{ site.data.profile.timezone }}</dd></div>
          <div><dt>Author Name</dt><dd>{{ site.data.profile.author_name }}</dd></div>
        </dl>
      </article>

      <article class="glass-card">
        <div class="card-label">MAIN CREATIVE LANES</div>
        <div class="tag-cloud profile-big-tags">
          <span>ROBLOX</span><span>LINGLOX</span><span>MINECRAFT JAVA</span>
          <span>MODDING</span><span>MAPPING</span><span>PUZZLES</span>
          <span>PROGRESSION</span><span>WORLDBUILDING</span><span>WRITING</span>
          <span>RHYTHM GAMES</span><span>TOOLS</span><span>WEB</span>
        </div>
      </article>

      <article class="glass-card">
        <div class="card-label">LANGUAGES / WEB</div>
        <div class="tag-cloud profile-big-tags">
          <span>LUA / LUAU</span><span>PYTHON</span><span>JAVA</span>
          <span>JAVASCRIPT</span><span>C#</span><span>C++</span><span>C</span>
          <span>HTML</span><span>CSS</span><span>JEKYLL</span><span>LIQUID</span>
        </div>
      </article>

      <article class="glass-card">
        <div class="card-label">DESIGN DNA</div>
        <div class="meter-list">
          <div class="meter-row"><span>Ideas</span><div class="meter"><i style="--value:100%"></i></div><b>CONSTANT</b></div>
          <div class="meter-row"><span>Detail</span><div class="meter"><i style="--value:100%"></i></div><b>MAXIMUM</b></div>
          <div class="meter-row"><span>Lore</span><div class="meter"><i style="--value:98%"></i></div><b>EXPANDING</b></div>
          <div class="meter-row"><span>Scope</span><div class="meter"><i style="--value:100%"></i></div><b>ESCALATING</b></div>
        </div>
      </article>
    </aside>
  </div>
</section>

<section class="section section-alt" id="personal-life">
  <div class="shell">
    <div class="section-heading">
      <p class="eyebrow">PROFILE // OUTSIDE THE PROJECT DATABASE</p>
      <h2>More Personal Stuff</h2>
      <p>A few actual-life details that are part of who I am, not just a list of things I build.</p>
    </div>

    <div class="personal-life-grid">
      <article class="glass-card prose" markdown="1">
        ## The basic stuff

        I'm **18** and based in **Texas, USA**. Online, I usually go by **Naki**, **N4-K2**, or **Nawkies**, and those names tend to overlap with whatever I'm making at the time.

        Games and creative projects are a pretty big part of how I spend my free time. I bounce between programming, map-building, writing, avatar customization, rhythm-game stuff, modding, and whatever new idea has managed to take over my brain that week.

        I am very much the kind of person who gets attached to the details. If I like a game, character, mechanic, avatar, or fictional setting, I usually want to understand it, customize it, document it, rebuild part of it, or make something inspired by it.
      </article>

      <article class="glass-card prose" markdown="1">
        ## Roblox is also a fashion problem

        Roblox is not just a development platform for me. I spend a lot of time on **avatar creation, outfit collecting, catalog browsing, horror games, and completely random experiences**.

        I've built up **150+ Roblox outfits**, and I change avatars often enough that one permanent look has never really been the point. A lot of the fun for me is experimenting with different themes, accessories, creature designs, and visual identities.

        I also own **Korblox Deathspeaker**. Buying it sounded better before I actually bought it, and it became one of those purchases where the immediate reaction was basically: *yeah, I kind of regret that.*
      </article>

      <article class="glass-card prose" markdown="1">
        ## Family matters to me

        I don't put much family information online, but family is still important to me. One small example is that I put real thought into writing something meaningful for my **grandfather's 80th birthday** instead of treating it like a generic card message.

        That's probably one of the places where the storytelling side of me shows up outside fiction too: when something matters, I would rather make it personal and specific than just write the minimum and move on.
      </article>

      <article class="glass-card prose" markdown="1">
        ## How I tend to be with hobbies

        I rarely have only one interest active at once. I can be working on a giant Linglox map, changing a Roblox avatar, thinking about a Minecraft mod, charting something for a rhythm game, editing a character profile, and then deciding the website also needs another database section.

        I like **collecting, customizing, organizing, experimenting, and expanding things**. That shows up everywhere: avatars, game systems, advancement trees, prompt maps, fictional casts, wiki pages, and even this site itself.
      </article>
    </div>

    <aside class="public-boundary-note glass-card">
      <div class="card-label">PUBLIC PROFILE BOUNDARY</div>
      <p>This site intentionally keeps some real-life information private. I share enough to make the profile feel like me without turning a public website into a record of every personal detail.</p>
    </aside>
  </div>
</section>

<section class="section section-alt">
  <div class="shell">
    <div class="section-heading">
      <p class="eyebrow">PROFILE // WHAT I ACTUALLY MAKE</p>
      <h2>Main Creative Areas</h2>
    </div>

    <div class="directory-grid">
      <article class="directory-card"><span class="directory-index">01</span><h3>Roblox / Linglox</h3><p>Huge maps, prompt placement, zones, puzzles, parkour, secrets, collectibles, traps, map tooling, and experimental systems.</p></article>
      <article class="directory-card"><span class="directory-index">02</span><h3>Minecraft Java</h3><p>Mods, advancements, educational mechanics, progression systems, puzzle concepts, and large content registries.</p></article>
      <article class="directory-card"><span class="directory-index">03</span><h3>Writing</h3><p>Character-heavy fiction, nonhuman species, relationship arcs, LitRPG/progression ideas, canon tracking, and very large character bibles.</p></article>
      <article class="directory-card"><span class="directory-index">04</span><h3>Tools & Automation</h3><p>Importers, converters, generators, scripts, data processing, web tools, and anything that removes repetitive work from a project.</p></article>
      <article class="directory-card"><span class="directory-index">05</span><h3>Rhythm / Charting</h3><p>Just Dance, FNF-related projects, osu!mania charting, song timing, scroll-speed changes, and music-driven game mechanics.</p></article>
      <article class="directory-card"><span class="directory-index">06</span><h3>Web / Databases</h3><p>Sites like this one: dark, searchable, data-driven, over-detailed, and designed to hold much more information than a normal bio page.</p></article>
    </div>
  </div>
</section>

<section class="section">
  <div class="shell">
    <div class="section-heading">
      <p class="eyebrow">PROFILE // CURRENT MAJOR PROJECTS</p>
      <h2>Project Constellation</h2>
    </div>
    <div class="project-grid">
      {% for project in site.projects %}
        {% include cards/project-card.html project=project %}
      {% endfor %}
    </div>
  </div>
</section>

<section class="section section-alt">
  <div class="shell">
    <div class="section-heading">
      <p class="eyebrow">TAHAUFYA // WRITER REFERENCE</p>
      <h2>Character Bible</h2>
      <p>The full current-cast-only bible is now part of the site, including all 25 active dossiers and the original PDF.</p>
    </div>
    <div class="section-actions">
      <a class="button button-primary" href="{{ '/character-bible/' | relative_url }}">OPEN CHARACTER BIBLE</a>
    </div>
  </div>
</section>

<section class="section">
  <div class="shell">
    <div class="section-heading">
      <p class="eyebrow">PROFILE // PUBLIC LINKS</p>
      <h2>Where I Am Online</h2>
      <p>These are the public profiles I actually use for code, Roblox, and writing.</p>
    </div>
    <div class="link-grid">
      {% for link in site.data.links %}
        {% include cards/link-card.html link=link %}
      {% endfor %}
    </div>
  </div>
</section>


<!-- OUTSIDE_THE_NOISE_HINT: the author profile is not the only profile that learned your name -->
