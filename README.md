<img width="1280" height="860" alt="playbook-flow" src="https://github.com/user-attachments/assets/965236a9-9eaa-4685-8b52-6e18bb0c7662" />
<svg width="1280" height="860" viewBox="0 0 1280 860" xmlns="http://www.w3.org/2000/svg" font-family="Segoe UI, system-ui, sans-serif">
  <!-- Azure Portal Top Bar -->
  <rect width="1280" height="48" fill="#1b1b1b"/>
  <text x="16" y="30" fill="white" font-size="14" font-weight="600">≡  Microsoft Azure</text>
  <rect x="240" y="10" width="400" height="28" rx="4" fill="#2d2d2d"/>
  <text x="256" y="29" fill="#888" font-size="13">🔍  Search resources, services, and docs</text>
  <text x="1100" y="30" fill="#aaa" font-size="12">jsmith@contoso.com</text>

  <!-- Left Sidebar -->
  <rect x="0" y="48" width="52" height="812" fill="#252525"/>

  <!-- Main Content -->
  <rect x="52" y="48" width="1228" height="812" fill="#f3f2f1"/>

  <!-- Breadcrumb -->
  <rect x="52" y="48" width="1228" height="44" fill="white" stroke="#e1dfdd" stroke-width="1"/>
  <text x="68" y="75" fill="#0078d4" font-size="13">Home</text>
  <text x="110" y="75" fill="#605e5c" font-size="13"> &gt; Logic Apps</text>
  <text x="200" y="75" fill="#605e5c" font-size="13"> &gt; sentinel-suspicious-signin-response</text>
  <text x="450" y="75" fill="#605e5c" font-size="13"> &gt; Logic app designer</text>

  <!-- Page Header -->
  <rect x="52" y="92" width="1228" height="56" fill="white" stroke="#e1dfdd" stroke-width="1"/>
  <text x="68" y="118" fill="#323130" font-size="20" font-weight="600">Logic app designer</text>
  <text x="68" y="138" fill="#605e5c" font-size="13">sentinel-suspicious-signin-response · East US · Running</text>
  <!-- Action buttons -->
  <rect x="930" y="104" width="86" height="28" rx="2" fill="#0078d4"/>
  <text x="946" y="122" fill="white" font-size="12">💾 Save</text>
  <rect x="1024" y="104" width="86" height="28" rx="2" fill="white" stroke="#8a8886" stroke-width="1"/>
  <text x="1038" y="122" fill="#323130" font-size="12">▶ Run</text>
  <rect x="1118" y="104" width="86" height="28" rx="2" fill="white" stroke="#8a8886" stroke-width="1"/>
  <text x="1132" y="122" fill="#323130" font-size="12">🔍 Code view</text>
  <rect x="1210" y="104" width="54" height="28" rx="2" fill="white" stroke="#8a8886" stroke-width="1"/>
  <text x="1224" y="122" fill="#323130" font-size="12">...</text>

  <!-- Designer toolbar -->
  <rect x="52" y="148" width="1228" height="40" fill="#faf9f8" stroke="#e1dfdd" stroke-width="1"/>
  <text x="80" y="173" fill="#605e5c" font-size="12">🔎 Search connectors</text>
  <text x="240" y="173" fill="#605e5c" font-size="12">⊕ Add action</text>
  <text x="350" y="173" fill="#605e5c" font-size="12">🗑 Delete</text>
  <text x="440" y="173" fill="#605e5c" font-size="12">🔄 Refresh</text>
  <text x="1120" y="173" fill="#605e5c" font-size="12">Zoom: 90% ➕  ➖</text>

  <!-- Designer canvas -->
  <rect x="52" y="188" width="1228" height="672" fill="#f0f4f8"/>
  <!-- Grid dots background -->
  <pattern id="grid" width="20" height="20" patternUnits="userSpaceOnUse">
    <circle cx="1" cy="1" r="0.8" fill="#c8d4de" opacity="0.6"/>
  </pattern>
  <rect x="52" y="188" width="1228" height="672" fill="url(#grid)"/>

  <!-- STEP 1: Trigger -->
  <rect x="480" y="208" width="320" height="68" rx="6" fill="white" stroke="#0078d4" stroke-width="2" filter="drop-shadow(0 2px 6px rgba(0,0,0,0.12))"/>
  <rect x="480" y="208" width="56" height="68" rx="6" fill="#0078d4"/>
  <text x="494" y="238" fill="white" font-size="16">⚡</text>
  <text x="494" y="262" fill="white" font-size="10">Trigger</text>
  <text x="546" y="232" fill="#323130" font-size="13" font-weight="600">When a Microsoft Sentinel</text>
  <text x="546" y="250" fill="#323130" font-size="13" font-weight="600">incident is created</text>
  <text x="546" y="268" fill="#888" font-size="11">Microsoft Sentinel · Trigger</text>
  <!-- Success badge -->
  <rect x="748" y="214" width="44" height="18" rx="9" fill="#dff6dd"/>
  <text x="756" y="226" fill="#107c10" font-size="10" font-weight="600">✓ OK</text>

  <!-- Connector line -->
  <line x1="640" y1="276" x2="640" y2="304" stroke="#c8c6c4" stroke-width="1.5" stroke-dasharray="4,2"/>
  <polygon points="636,300 640,308 644,300" fill="#c8c6c4"/>

  <!-- STEP 2: Parse entities -->
  <rect x="480" y="308" width="320" height="68" rx="6" fill="white" stroke="#c8c6c4" stroke-width="1.5" filter="drop-shadow(0 2px 6px rgba(0,0,0,0.08))"/>
  <rect x="480" y="308" width="56" height="68" rx="6" fill="#009ad9"/>
  <text x="494" y="338" fill="white" font-size="16">🔍</text>
  <text x="494" y="358" fill="white" font-size="10">Action</text>
  <text x="546" y="330" fill="#323130" font-size="13" font-weight="600">Entities - Get Accounts</text>
  <text x="546" y="350" fill="#605e5c" font-size="12">Parse incident entity list</text>
  <text x="546" y="368" fill="#888" font-size="11">Microsoft Sentinel · Action</text>
  <rect x="748" y="314" width="44" height="18" rx="9" fill="#dff6dd"/>
  <text x="756" y="326" fill="#107c10" font-size="10" font-weight="600">✓ OK</text>

  <!-- Connector line -->
  <line x1="640" y1="376" x2="640" y2="404" stroke="#c8c6c4" stroke-width="1.5" stroke-dasharray="4,2"/>
  <polygon points="636,400 640,408 644,400" fill="#c8c6c4"/>

  <!-- STEP 3: Post Teams message -->
  <rect x="480" y="408" width="320" height="68" rx="6" fill="white" stroke="#c8c6c4" stroke-width="1.5" filter="drop-shadow(0 2px 6px rgba(0,0,0,0.08))"/>
  <rect x="480" y="408" width="56" height="68" rx="6" fill="#6264a7"/>
  <text x="494" y="438" fill="white" font-size="16">💬</text>
  <text x="494" y="458" fill="white" font-size="10">Action</text>
  <text x="546" y="430" fill="#323130" font-size="13" font-weight="600">Post message in a chat</text>
  <text x="546" y="450" fill="#605e5c" font-size="12">Notify SOC channel — #alerts-high</text>
  <text x="546" y="468" fill="#888" font-size="11">Microsoft Teams · Action</text>
  <rect x="748" y="414" width="44" height="18" rx="9" fill="#dff6dd"/>
  <text x="756" y="426" fill="#107c10" font-size="10" font-weight="600">✓ OK</text>

  <!-- Connector line -->
  <line x1="640" y1="476" x2="640" y2="504" stroke="#c8c6c4" stroke-width="1.5" stroke-dasharray="4,2"/>
  <polygon points="636,500 640,508 644,500" fill="#c8c6c4"/>

  <!-- STEP 4: Approval email -->
  <rect x="480" y="508" width="320" height="68" rx="6" fill="white" stroke="#c8c6c4" stroke-width="1.5" filter="drop-shadow(0 2px 6px rgba(0,0,0,0.08))"/>
  <rect x="480" y="508" width="56" height="68" rx="6" fill="#0072c6"/>
  <text x="494" y="538" fill="white" font-size="16">📧</text>
  <text x="494" y="558" fill="white" font-size="10">Action</text>
  <text x="546" y="530" fill="#323130" font-size="13" font-weight="600">Send approval email</text>
  <text x="546" y="550" fill="#605e5c" font-size="12">Request analyst action — Approve/Reject</text>
  <text x="546" y="568" fill="#888" font-size="11">Office 365 Outlook · Action</text>
  <rect x="748" y="514" width="70" height="18" rx="9" fill="#fff4ce"/>
  <text x="752" y="526" fill="#835b00" font-size="10" font-weight="600">⏱ Waiting</text>

  <!-- Connector line -->
  <line x1="640" y1="576" x2="640" y2="604" stroke="#c8c6c4" stroke-width="1.5" stroke-dasharray="4,2"/>
  <polygon points="636,600 640,608 644,600" fill="#c8c6c4"/>

  <!-- STEP 5: Condition (branch) -->
  <rect x="440" y="608" width="400" height="54" rx="6" fill="white" stroke="#ca5010" stroke-width="1.5" filter="drop-shadow(0 2px 6px rgba(0,0,0,0.08))"/>
  <rect x="440" y="608" width="56" height="54" rx="6" fill="#ca5010"/>
  <text x="456" y="632" fill="white" font-size="16">🔀</text>
  <text x="456" y="652" fill="white" font-size="10">Control</text>
  <text x="506" y="628" fill="#323130" font-size="13" font-weight="600">Condition: Approval response equals</text>
  <text x="506" y="646" fill="#605e5c" font-size="12">'Approve'  — Timeout: 4h</text>
  <text x="506" y="660" fill="#888" font-size="10">⚠ Unapproved requests will auto-close after timeout</text>

  <!-- Branch lines -->
  <line x1="520" y1="662" x2="520" y2="688" stroke="#c8c6c4" stroke-width="1.5"/>
  <line x1="760" y1="662" x2="760" y2="688" stroke="#c8c6c4" stroke-width="1.5"/>
  <line x1="520" y1="688" x2="760" y2="688" stroke="#c8c6c4" stroke-width="1.5"/>
  <line x1="520" y1="688" x2="520" y2="706" stroke="#c8c6c4" stroke-width="1.5"/>
  <line x1="760" y1="688" x2="760" y2="706" stroke="#c8c6c4" stroke-width="1.5"/>
  <polygon points="516,702 520,710 524,702" fill="#c8c6c4"/>
  <polygon points="756,702 760,710 764,702" fill="#c8c6c4"/>
  <!-- Branch labels -->
  <rect x="466" y="676" width="36" height="18" rx="9" fill="#dff6dd"/>
  <text x="472" y="689" fill="#107c10" font-size="11" font-weight="600">Yes</text>
  <rect x="738" y="676" width="28" height="18" rx="9" fill="#fde7e9"/>
  <text x="745" y="689" fill="#a4262c" font-size="11" font-weight="600">No</text>

  <!-- YES branch: Disable account -->
  <rect x="358" y="710" width="324" height="68" rx="6" fill="white" stroke="#107c10" stroke-width="1.5" filter="drop-shadow(0 2px 6px rgba(0,0,0,0.08))"/>
  <rect x="358" y="710" width="56" height="68" rx="6" fill="#107c10"/>
  <text x="372" y="740" fill="white" font-size="14">🔒</text>
  <text x="372" y="762" fill="white" font-size="10">Action</text>
  <text x="424" y="730" fill="#323130" font-size="13" font-weight="600">Disable Azure AD user account</text>
  <text x="424" y="750" fill="#605e5c" font-size="12">User: @{triggerBody()?['incidentEntities']}</text>
  <text x="424" y="770" fill="#888" font-size="11">Microsoft Entra ID · Action</text>

  <!-- NO branch: add comment -->
  <rect x="598" y="710" width="324" height="68" rx="6" fill="white" stroke="#a4262c" stroke-width="1.5" filter="drop-shadow(0 2px 6px rgba(0,0,0,0.08))"/>
  <rect x="598" y="710" width="56" height="68" rx="6" fill="#a4262c"/>
  <text x="612" y="740" fill="white" font-size="14">🚫</text>
  <text x="612" y="762" fill="white" font-size="10">Action</text>
  <text x="664" y="730" fill="#323130" font-size="13" font-weight="600">Add comment to incident</text>
  <text x="664" y="750" fill="#605e5c" font-size="12">Status: Containment not approved</text>
  <text x="664" y="770" fill="#888" font-size="11">Microsoft Sentinel · Action</text>

  <!-- Converge lines -->
  <line x1="520" y1="778" x2="520" y2="800" stroke="#c8c6c4" stroke-width="1.5"/>
  <line x1="760" y1="778" x2="760" y2="800" stroke="#c8c6c4" stroke-width="1.5"/>
  <line x1="520" y1="800" x2="760" y2="800" stroke="#c8c6c4" stroke-width="1.5"/>
  <line x1="640" y1="800" x2="640" y2="812" stroke="#c8c6c4" stroke-width="1.5"/>
  <polygon points="636,808 640,816 644,808" fill="#c8c6c4"/>

  <!-- Final step: Update incident -->
  <rect x="480" y="818" width="320" height="28" rx="6" fill="white" stroke="#c8c6c4" stroke-width="1.5" filter="drop-shadow(0 2px 4px rgba(0,0,0,0.06))"/>
  <rect x="480" y="818" width="40" height="28" rx="6" fill="#0078d4"/>
  <text x="490" y="836" fill="white" font-size="11">✔</text>
  <text x="530" y="836" fill="#323130" font-size="12" font-weight="600">Update incident status + add response tag</text>
  <text x="756" y="836" fill="#888" font-size="10">Sentinel</text>

  <!-- Run info panel at right -->
  <rect x="1030" y="208" width="230" height="330" rx="4" fill="white" stroke="#e1dfdd" stroke-width="1"/>
  <rect x="1030" y="208" width="230" height="40" fill="#faf9f8" stroke="#e1dfdd" stroke-width="1"/>
  <text x="1046" y="232" fill="#323130" font-size="13" font-weight="600">Recent runs</text>
  <text x="1230" y="232" fill="#0078d4" font-size="12">All →</text>

  <rect x="1046" y="258" width="8" height="8" rx="2" fill="#107c10"/>
  <text x="1060" y="267" fill="#323130" font-size="12">Succeeded</text>
  <text x="1046" y="282" fill="#888" font-size="11">May 12 · 09:14 UTC · 4m 22s</text>
  <line x1="1046" y1="292" x2="1244" y2="292" stroke="#edebe9" stroke-width="1"/>

  <rect x="1046" y="304" width="8" height="8" rx="2" fill="#107c10"/>
  <text x="1060" y="313" fill="#323130" font-size="12">Succeeded</text>
  <text x="1046" y="328" fill="#888" font-size="11">May 11 · 14:32 UTC · 3m 08s</text>
  <line x1="1046" y1="338" x2="1244" y2="338" stroke="#edebe9" stroke-width="1"/>

  <rect x="1046" y="350" width="8" height="8" rx="2" fill="#d83b01"/>
  <text x="1060" y="359" fill="#323130" font-size="12">Failed</text>
  <text x="1046" y="374" fill="#888" font-size="11">May 11 · 08:17 UTC · 12s</text>
  <text x="1046" y="388" fill="#d83b01" font-size="10">Approval timeout — no response</text>
  <line x1="1046" y1="396" x2="1244" y2="396" stroke="#edebe9" stroke-width="1"/>

  <rect x="1046" y="408" width="8" height="8" rx="2" fill="#107c10"/>
  <text x="1060" y="417" fill="#323130" font-size="12">Succeeded</text>
  <text x="1046" y="432" fill="#888" font-size="11">May 10 · 22:05 UTC · 5m 47s</text>
  <line x1="1046" y1="442" x2="1244" y2="442" stroke="#edebe9" stroke-width="1"/>

  <rect x="1046" y="454" width="8" height="8" rx="2" fill="#107c10"/>
  <text x="1060" y="463" fill="#323130" font-size="12">Succeeded</text>
  <text x="1046" y="478" fill="#888" font-size="11">May 10 · 17:50 UTC · 3m 55s</text>
  <line x1="1046" y1="488" x2="1244" y2="488" stroke="#edebe9" stroke-width="1"/>
  <text x="1046" y="526" fill="#888" font-size="11">5 of 12 runs shown</text>

  <!-- Playbook properties -->
  <rect x="1030" y="558" width="230" height="180" rx="4" fill="white" stroke="#e1dfdd" stroke-width="1"/>
  <rect x="1030" y="558" width="230" height="36" fill="#faf9f8" stroke="#e1dfdd" stroke-width="1"/>
  <text x="1046" y="580" fill="#323130" font-size="13" font-weight="600">Playbook properties</text>
  <text x="1046" y="614" fill="#605e5c" font-size="11" font-weight="600">NAME</text>
  <text x="1046" y="630" fill="#323130" font-size="12">sentinel-suspicious-signin-response</text>
  <text x="1046" y="650" fill="#605e5c" font-size="11" font-weight="600">SUBSCRIPTION</text>
  <text x="1046" y="666" fill="#323130" font-size="12">Contoso-Azure-Sub-001</text>
  <text x="1046" y="686" fill="#605e5c" font-size="11" font-weight="600">RESOURCE GROUP</text>
  <text x="1046" y="702" fill="#323130" font-size="12">rg-sentinel-prod-eastus</text>
  <text x="1046" y="722" fill="#605e5c" font-size="11" font-weight="600">LOCATION</text>
  <text x="1046" y="738" fill="#323130" font-size="12">East US</text>
</svg>
