# Joe Eichenbaum

I'm a partner at [17A](https://group17a.com), a consulting firm that works with state and local governments. Day to day I'm some mix of developer, chief of staff, and CTO for city halls, county IT shops, and state agencies. Most of that work is confidential. What's public is mostly my adjacent curiosities, and most of those live at [gizmowarehouse.org](https://gizmowarehouse.org).

## Start here

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://gizmowarehouse.org/gizmo/medicaid-work-requirements"><img src="https://gizmowarehouse.org/og/medicaid-work-requirements.png" alt="Medicaid work requirements explorer" width="100%"></a>
      <br><b><a href="https://gizmowarehouse.org/gizmo/medicaid-work-requirements">Who loses Medicaid in 2027</a></b><br>
      A nationwide, bottom-up model of the new federal work requirement. Who is at risk, where they live, and whether each state can verify work before the deadline. Live map, a brief for every state, and the methodology.
      <br><sub><a href="https://github.com/eichenbaumj/gizmowarehouse.org/tree/main/gizmos/medicaid-work-requirements">source and data</a></sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://gizmowarehouse.org/gizmo/public-private-compensation-comparison"><img src="https://gizmowarehouse.org/og/public-private-compensation-comparison.png" alt="High Floor, Low Ceiling" width="100%"></a>
      <br><b><a href="https://gizmowarehouse.org/gizmo/public-private-compensation-comparison">High Floor, Low Ceiling</a></b><br>
      Public pay holds its own at the bottom of the labor market and falls far behind at the top, exactly where private pay has soared. The public-sector pay gap by skill, by field, by level of government, and over time, from ACS microdata, BLS and BEA series, and city and state payrolls.
      <br><sub><a href="https://github.com/eichenbaumj/gizmowarehouse.org/tree/main/gizmos/public-private-compensation-comparison">source and data</a></sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://daf-yomi.dev"><img src="https://gizmowarehouse.org/og/daf-yomi.png" alt="Today's Daf" width="100%"></a>
      <br><b><a href="https://daf-yomi.dev">Today's Daf</a></b><br>
      The day's page of Talmud in English, with a short note written by an AI that says so. One Cloudflare Worker, no framework, no accounts, no tracking. A daily email if you want it.
      <br><sub><a href="https://github.com/eichenbaumj/daf-yomi">source</a> · <a href="https://gizmowarehouse.org/gizmo/daf-yomi">how I built it</a></sub>
    </td>
  </tr>
</table>

## How I work

- **I treat Claude Code like a somewhat bumbling CTO talking to his engineering team.** I describe what I want in plain language and ask for the whole thing. What comes back is either better than I asked for, not what I asked for at all, or something that looks right and isn't. My job is telling those apart, and steering the team towards my goals.
- **Claude Code does most of the typing,** in Python for analysis and React for anything with a map. Lovable when I want a front end in 10 minutes. Supabase for sign-in and the data that can't be public. Cloudflare Pages, Workers, and R2 for anything that should stay cheap and fast forever. Codex when I want a second opinion that didn't write the first one.
- **Plain language for skeptical readers.** The audience is a city council, a state CIO, or a federal reviewer. They get conclusions, not methods.
- **Every number traces to a source.** If I can't trace it, the page says so.

## More from the warehouse

| | |
|---|---|
| [Reducing Violent Crime Without New Budget, New Staff, or More Arrests](https://eichenbaumj.github.io/reducing-violence-whitepaper/) | A guide for city leaders, with Dallas's 2024 to 2025 implementation as the case study. |
| [Pricing the Fear of Data Centers](https://gizmowarehouse.org/gizmo/data-center-restriction-cost) | What a town gives up when it says no, a national map of restrictions, and the terms to demand if the answer is yes. |
| [The New Math on NYC's Public Grocery Stores](https://gizmowarehouse.org/gizmo/nyc-public-grocery-new-math) | A ten-year cost of the 30 percent discount promise, and what the same money would feed instead. |
| [NYC Property Tax: Who Pays, Who Doesn't](https://gizmowarehouse.org/gizmo/nyc-property-tax-map) | A parcel-level map of effective rates, and why two identical brownstones pay different bills. |
| [How to Save the Government from Microsoft Copilot](https://gizmowarehouse.org/gizmo/microsoft-copilot) | Why agencies default to Copilot, what the head-to-head numbers say, and a one-page procurement checklist. |
| [The Only Way to Start Is by Starting](https://gizmowarehouse.org/gizmo/only-way-to-start-is-by-starting) | How a state or local agency gets real value from AI in ninety days, with one accountable owner and one real piece of work. |
| [Jazz Fakebook Maker](https://github.com/eichenbaumj/fakebook-maker) | Plain-text chord charts in, a bookmarked PDF fake book out. Built for a laptop on a piano stand. |
| [Music Theory with LLMs](https://gizmowarehouse.org/gizmo/gospel-of-claude-code) | Gospel reharmonizations with Claude Code, and why next-chord prediction is a natural LLM task. |

## Where the work lives

Most of what I ship sits in private client repositories. The public ones are above. [gizmowarehouse.org](https://github.com/eichenbaumj/gizmowarehouse.org) is a generated mirror of the site plus the source behind every gizmo that is currently live. A sync gate publishes a gizmo's code only once the gizmo itself is.

If something here sparks something, write me at [joe@group17a.com](mailto:joe@group17a.com).
