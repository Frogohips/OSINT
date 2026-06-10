<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { background: transparent; }
  .readme { font-family: var(--font-mono); color: var(--color-text-primary); padding: 1.5rem 0; max-width: 680px; }
  .banner { background: #0d1117; border: 0.5px solid #30363d; border-radius: var(--border-radius-lg); padding: 2rem; margin-bottom: 1.5rem; text-align: center; }
  .banner-title { font-size: 22px; font-weight: 500; color: #58a6ff; letter-spacing: 2px; margin-bottom: 0.5rem; }
  .banner-sub { font-size: 13px; color: #8b949e; letter-spacing: 1px; }
  .badges { display: flex; gap: 8px; justify-content: center; flex-wrap: wrap; margin-top: 1rem; }
  .badge { font-size: 11px; padding: 3px 10px; border-radius: 20px; font-family: var(--font-mono); }
  .badge-blue { background: #1f3a5c; color: #58a6ff; border: 0.5px solid #1f6feb; }
  .badge-green { background: #1a3a25; color: #3fb950; border: 0.5px solid #238636; }
  .badge-purple { background: #2d1f5c; color: #bc8cff; border: 0.5px solid #6e40c9; }
  .section { margin-bottom: 1.5rem; }
  .section-header { display: flex; align-items: center; gap: 10px; margin-bottom: 1rem; padding-bottom: 0.5rem; border-bottom: 0.5px solid #30363d; }
  .section-title { font-size: 15px; font-weight: 500; color: #e6edf3; }
  .section-icon { font-size: 16px; color: #58a6ff; }
  .tool-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 10px; }
  .tool-card { background: #0d1117; border: 0.5px solid #30363d; border-radius: var(--border-radius-md); padding: 12px; transition: border-color 0.15s; cursor: default; }
  .tool-card:hover { border-color: #58a6ff; }
  .tool-name { font-size: 13px; font-weight: 500; color: #58a6ff; margin-bottom: 4px; }
  .tool-desc { font-size: 11px; color: #8b949e; line-height: 1.5; }
  .stat-row { display: flex; gap: 10px; margin-bottom: 1.5rem; }
  .stat-card { flex: 1; background: #0d1117; border: 0.5px solid #30363d; border-radius: var(--border-radius-md); padding: 12px; text-align: center; }
  .stat-val { font-size: 20px; font-weight: 500; color: #3fb950; }
  .stat-label { font-size: 11px; color: #8b949e; margin-top: 4px; }
  .focus-list { list-style: none; display: flex; flex-direction: column; gap: 8px; }
  .focus-item { display: flex; align-items: flex-start; gap: 10px; font-size: 13px; color: #c9d1d9; background: #0d1117; border: 0.5px solid #30363d; border-radius: var(--border-radius-md); padding: 10px 12px; }
  .focus-item .arrow { color: #3fb950; flex-shrink: 0; }
  .focus-label { color: #58a6ff; font-weight: 500; margin-right: 6px; }
  .divider { border: none; border-top: 0.5px solid #30363d; margin: 1.5rem 0; }
  .footer { text-align: center; font-size: 11px; color: #484f58; padding-top: 0.5rem; }
</style>

<div class="readme">
  <div class="banner">
    <div class="banner-title">[ OSINT TOOLKIT ]</div>
    <div class="banner-sub">open source intelligence — tools & methodologies</div>
    <div class="badges">
      <span class="badge badge-blue">reconnaissance</span>
      <span class="badge badge-green">investigation</span>
      <span class="badge badge-purple">geolocation</span>
    </div>
  </div>

  <div class="stat-row">
    <div class="stat-card">
      <div class="stat-val">15+</div>
      <div class="stat-label">tools</div>
    </div>
    <div class="stat-card">
      <div class="stat-val">5</div>
      <div class="stat-label">categories</div>
    </div>
    <div class="stat-card">
      <div class="stat-val">active</div>
      <div class="stat-label">status</div>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <i class="ti ti-radar section-icon" aria-hidden="true"></i>
      <span class="section-title">// focus areas</span>
    </div>
    <ul class="focus-list">
      <li class="focus-item"><span class="arrow">▸</span><span><span class="focus-label">Reconnaissance:</span>theHarvester, SpiderFoot, Sherlock</span></li>
      <li class="focus-item"><span class="arrow">▸</span><span><span class="focus-label">Search techniques:</span>Google Dorking, Pastebin analysis, OSINT Framework</span></li>
      <li class="focus-item"><span class="arrow">▸</span><span><span class="focus-label">Social media:</span>manual profiling, Wayback Machine, platform-native tools</span></li>
      <li class="focus-item"><span class="arrow">▸</span><span><span class="focus-label">Username & email:</span>Whatsmyname, IDCrawl, Epieos, GHunt, Holehe, Blackbird</span></li>
      <li class="focus-item"><span class="arrow">▸</span><span><span class="focus-label">Geolocation:</span>Google Earth, Overpass Turbo, Mapillary, reverse image search</span></li>
    </ul>
  </div>

  <div class="section">
    <div class="section-header">
      <i class="ti ti-tools section-icon" aria-hidden="true"></i>
      <span class="section-title">// toolkit</span>
    </div>
    <div class="tool-grid">
      <div class="tool-card">
        <div class="tool-name">theHarvester</div>
        <div class="tool-desc">Email, subdomain & host enumeration from public sources</div>
      </div>
      <div class="tool-card">
        <div class="tool-name">Sherlock</div>
        <div class="tool-desc">Username hunting across hundreds of platforms</div>
      </div>
      <div class="tool-card">
        <div class="tool-name">SpiderFoot</div>
        <div class="tool-desc">Automated OSINT reconnaissance across multiple data sources</div>
      </div>
      <div class="tool-card">
        <div class="tool-name">Blackbird</div>
        <div class="tool-desc">Fast username & email investigation across social platforms</div>
      </div>
      <div class="tool-card">
        <div class="tool-name">Holehe</div>
        <div class="tool-desc">Check where an email address has been used to register accounts</div>
      </div>
      <div class="tool-card">
        <div class="tool-name">GHunt</div>
        <div class="tool-desc">Locate Google Maps accounts and extract data from Drive links</div>
      </div>
      <div class="tool-card">
        <div class="tool-name">Epieos</div>
        <div class="tool-desc">Check if an email has an associated Google Maps presence</div>
      </div>
      <div class="tool-card">
        <div class="tool-name">Whatsmyname</div>
        <div class="tool-desc">Web-based username search across major platforms</div>
      </div>
      <div class="tool-card">
        <div class="tool-name">Google Dorking</div>
        <div class="tool-desc">Advanced search operators to surface hidden or exposed data</div>
      </div>
      <div class="tool-card">
        <div class="tool-name">Pastebin analysis</div>
        <div class="tool-desc">Scanning paste sites for leaked credentials and sensitive data</div>
      </div>
      <div class="tool-card">
        <div class="tool-name">Overpass Turbo</div>
        <div class="tool-desc">Geographic queries against OpenStreetMap for geolocation work</div>
      </div>
      <div class="tool-card">
        <div class="tool-name">OSINT Framework</div>
        <div class="tool-desc">Curated directory of categorised OSINT resources and tools</div>
      </div>
    </div>
  </div>

  <hr class="divider">
  <div class="footer">// methodologies documented via writeups — passive recon only unless otherwise stated</div>
</div>
