{
  `title`: `github_profile_improvement_guide`,
  `loading_messages`: [
    `Building your profile checklist...`
  ],
  `widget_code`: `
<style>
  .section { margin-bottom: 2rem; }
  .section-title { font-size: 15px; font-weight: 500; color: var(--color-text-primary); margin: 0 0 12px; padding-bottom: 8px; border-bottom: 0.5px solid var(--color-border-tertiary); }
  .tip-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); padding: 12px 14px; margin-bottom: 8px; display: flex; gap: 12px; align-items: flex-start; }
  .icon { width: 28px; height: 28px; border-radius: 6px; display: flex; align-items: center; justify-content: center; font-size: 13px; flex-shrink: 0; }
  .icon-red { background: #FCEBEB; color: #A32D2D; }
  .icon-amber { background: #FAEEDA; color: #854F0B; }
  .icon-teal { background: #E1F5EE; color: #0F6E56; }
  .icon-blue { background: #E6F1FB; color: #185FA5; }
  .tip-title { font-size: 13px; font-weight: 500; color: var(--color-text-primary); margin: 0 0 3px; }
  .tip-desc { font-size: 12px; color: var(--color-text-secondary); margin: 0; line-height: 1.5; }
  .badge { display: inline-block; font-size: 11px; padding: 2px 8px; border-radius: 20px; margin-left: 6px; font-weight: 500; }
  .badge-red { background: #FCEBEB; color: #A32D2D; }
  .badge-amber { background: #FAEEDA; color: #854F0B; }
  .badge-teal { background: #E1F5EE; color: #0F6E56; }
  .score-row { display: flex; gap: 10px; margin-bottom: 1.5rem; }
  .score-card { flex: 1; background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 12px; text-align: center; }
  .score-label { font-size: 11px; color: var(--color-text-secondary); margin: 0 0 4px; }
  .score-val { font-size: 20px; font-weight: 500; color: var(--color-text-primary); margin: 0; }
</style>

<div style=\"padding: 1rem 0;\">
  <div class=\"section\">
    <p class=\"section-title\">Profile essentials checklist</p>

    <div class=\"tip-card\">
      <div class=\"icon icon-red\">!</div>
      <div>
        <p class=\"tip-title\">Profile README <span class=\"badge badge-red\">High priority</span></p>
        <p class=\"tip-desc\">Create a special repo named exactly as your username (ravi64r/ravi64r). Add a README.md with your intro, skills, tech stack, and what you're working on.</p>
      </div>
    </div>

    <div class=\"tip-card\">
      <div class=\"icon icon-red\">!</div>
      <div>
        <p class=\"tip-title\">Profile photo <span class=\"badge badge-red\">High priority</span></p>
        <p class=\"tip-desc\">Add a clear, professional photo. Profiles with photos get significantly more attention than those without.</p>
      </div>
    </div>

    <div class=\"tip-card\">
      <div class=\"icon icon-red\">!</div>
      <div>
        <p class=\"tip-title\">Bio & location <span class=\"badge badge-red\">High priority</span></p>
        <p class=\"tip-desc\">Write a short bio (e.g. \"Full-stack developer | Python & React | Based in Ahmedabad\"). Add your city, website, LinkedIn, and Twitter if you have them.</p>
      </div>
    </div>

    <div class=\"tip-card\">
      <div class=\"icon icon-amber\">~</div>
      <div>
        <p class=\"tip-title\">Pin your best repositories <span class=\"badge badge-amber\">Medium priority</span></p>
        <p class=\"tip-desc\">Pin 4–6 of your strongest projects on your profile. Visitors see these first — make sure they have descriptions and topics/tags.</p>
      </div>
    </div>

    <div class=\"tip-card\">
      <div class=\"icon icon-amber\">~</div>
      <div>
        <p class=\"tip-title\">Repository descriptions & topics <span class=\"badge badge-amber\">Medium priority</span></p>
        <p class=\"tip-desc\">Every public repo should have a clear 1-line description and relevant topic tags (e.g. \"python\", \"web-scraping\", \"react\") for discoverability.</p>
      </div>
    </div>

    <div class=\"tip-card\">
      <div class=\"icon icon-amber\">~</div>
      <div>
        <p class=\"tip-title\">README files in all repos <span class=\"badge badge-amber\">Medium priority</span></p>
        <p class=\"tip-desc\">Each project should have a README explaining: what it does, how to install/run it, screenshots or demo GIFs, and tech stack used.</p>
      </div>
    </div>

    <div class=\"tip-card\">
      <div class=\"icon icon-teal\">+</div>
      <div>
        <p class=\"tip-title\">Contribution streak <span class=\"badge badge-teal\">Ongoing</span></p>
        <p class=\"tip-desc\">Aim for regular commits. Even small improvements count — documentation fixes, bug reports, and small features all add to your green squares.</p>
      </div>
    </div>

    <div class=\"tip-card\">
      <div class=\"icon icon-teal\">+</div>
      <div>
        <p class=\"tip-title\">GitHub Stats & badges in README <span class=\"badge badge-teal\">Bonus</span></p>
        <p class=\"tip-desc\">Add dynamic stats cards using github-readme-stats by anuraghazra. Shows your top languages, total commits, and streak — makes your README pop.</p>
      </div>
    </div>

    <div class=\"tip-card\">
      <div class=\"icon icon-blue\">i</div>
      <div>
        <p class=\"tip-title\">Contribute to open source <span class=\"badge badge-teal\">Bonus</span></p>
        <p class=\"tip-desc\">Even small contributions to popular repos (bug fixes, docs) are visible on your profile and show collaboration skills to employers.</p>
      </div>
    </div>
  </div>

  <div class=\"section\">
    <p class=\"section-title\">Profile README template to get started</p>
    <div style=\"background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 14px; font-family: var(--font-mono); font-size: 12px; color: var(--color-text-primary); line-height: 1.8; white-space: pre-wrap;\">## Hi there, I'm Ravi 👋

🔭 I'm currently working on: [Your Project]
🌱 I'm learning: [e.g. Machine Learning / DevOps]
💬 Ask me about: [Your Strengths]
📫 Reach me: your@email.com
⚡ Fun fact: [Something fun about you]

### Tech Stack
![Python](https://img.shields.io/badge/-Python-blue)
![React](https://img.shields.io/badge/-React-61DAFB)

### GitHub Stats
![Stats](https://github-readme-stats.vercel.app/api?username=ravi64r)</div>
  </div>

  <div class=\"section\">
    <p class=\"section-title\">Useful resources</p>
    <div class=\"tip-card\">
      <div class=\"icon icon-blue\">→</div>
      <div>
        <p class=\"tip-title\">README generator</p>
        <p class=\"tip-desc\">rahuldkjain.github.io/gh-profile-readme-generator — fill in your details and get a full README in seconds.</p>
      </div>
    </div>
    <div class=\"tip-card\">
      <div class=\"icon icon-blue\">→</div>
      <div>
        <p class=\"tip-title\">GitHub stats cards</p>
        <p class=\"tip-desc\">github.com/anuraghazra/github-readme-stats — dynamic cards showing your contribution stats, top languages, and streaks.</p>
      </div>
    </div>
    <div class=\"tip-card\">
      <div class=\"icon icon-blue\">→</div>
      <div>
        <p class=\"tip-title\">Shields.io badges</p>
        <p class=\"tip-desc\">shields.io — create custom badges for your tech stack, license, version, and more.</p>
      </div>
    </div>
  </div>
</div>
`
}
