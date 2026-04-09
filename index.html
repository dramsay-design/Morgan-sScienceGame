<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mission Matter: Grade 8 Science Challenge</title>
  <style>
    :root{
      --bg1:#1b1038;
      --bg2:#2b1460;
      --panel:#23164e;
      --panel2:#2c1d63;
      --accent1:#ff8a1f;
      --accent2:#8f5cff;
      --accent3:#3aa6ff;
      --text:#f6f3ff;
      --muted:#cbc4ea;
      --good:#32d17c;
      --bad:#ff5e7e;
      --line:rgba(255,255,255,.12);
      --card-shadow:0 14px 40px rgba(0,0,0,.35);
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;font-family:Arial,Helvetica,sans-serif;background:linear-gradient(180deg,var(--bg1),#130b2b 45%, #0f1331);color:var(--text)}
    body{min-height:100vh}
    body.block-copy{-webkit-user-select:none;user-select:none}
    .hidden{display:none!important}
    .app{max-width:1180px;margin:0 auto;padding:20px}
    .screen{display:none;min-height:calc(100vh - 40px)}
    .screen.active{display:block}
    .hero,.panel,.question-card,.certificate{background:linear-gradient(180deg,rgba(255,255,255,.05),rgba(255,255,255,.02));border:1px solid var(--line);border-radius:22px;box-shadow:var(--card-shadow)}
    .hero{padding:28px;display:grid;grid-template-columns:1.1fr .9fr;gap:22px;align-items:start}
    h1,h2,h3{margin-top:0}
    h1{font-size:2.2rem;line-height:1.05;margin-bottom:10px}
    .sub{color:var(--muted);font-size:1rem;line-height:1.55}
    .message-box{background:rgba(58,166,255,.1);border:1px solid rgba(58,166,255,.25);padding:16px;border-radius:16px;margin:18px 0}
    .name-box,.controls,.question-nav,.periodic-panel,.legend,.score-bar,.table-grid,.drag-zone,.drop-row,.option-row{display:flex}
    .name-box{gap:10px;flex-wrap:wrap;margin-top:18px}
    input[type="text"], input[type="number"], select{
      background:#120c2c;color:var(--text);border:1px solid var(--line);border-radius:14px;padding:14px 14px;font-size:1rem;outline:none
    }
    #studentName{min-width:280px;flex:1}
    button{border:none;border-radius:16px;padding:14px 18px;font-weight:700;font-size:1rem;cursor:pointer;transition:.2s transform,.2s opacity,.2s background}
    button:hover{transform:translateY(-1px)}
    .primary{background:linear-gradient(90deg,var(--accent2),var(--accent1));color:white}
    .secondary{background:rgba(255,255,255,.08);color:var(--text);border:1px solid var(--line)}
    .tertiary{background:linear-gradient(90deg,var(--accent3),var(--accent2));color:white}
    .panel{padding:20px}
    .front-grid{display:grid;grid-template-columns:1fr;gap:18px}
    .periodic-panel{flex-direction:column;gap:14px;padding:18px}
    .tiny{font-size:.88rem;color:var(--muted)}
    .periodic-wrap{overflow:auto;background:#130d2d;border-radius:18px;padding:14px;border:1px solid var(--line)}
    .periodic-table{display:grid;grid-template-columns:repeat(18,56px);gap:6px;min-width:max-content}
    .el,.blank,.series-label{height:54px;border-radius:12px;display:flex;align-items:center;justify-content:center;text-align:center;font-size:.82rem;padding:4px}
    .blank{background:transparent;border:1px dashed transparent}
    .el{position:relative;background:#23184f;border:1px solid rgba(255,255,255,.12);font-weight:700}
    .el small{position:absolute;top:4px;left:6px;font-size:.62rem;opacity:.85}
    .el span{display:block;font-size:1rem}
    .metal{background:rgba(143,92,255,.24)}
    .nonmetal{background:rgba(58,166,255,.22)}
    .metalloid{background:rgba(255,138,31,.24)}
    .noble{background:rgba(50,209,124,.24)}
    .legend{gap:10px;flex-wrap:wrap}
    .pill{padding:8px 12px;border-radius:999px;font-size:.85rem;border:1px solid var(--line)}
    .pill.metal{background:rgba(143,92,255,.24)}
    .pill.nonmetal{background:rgba(58,166,255,.22)}
    .pill.metalloid{background:rgba(255,138,31,.24)}
    .pill.noble{background:rgba(50,209,124,.24)}
    .topbar{display:flex;gap:14px;align-items:center;justify-content:space-between;margin-bottom:18px;flex-wrap:wrap}
    .score-bar{gap:12px;align-items:center;flex-wrap:wrap}
    .progress-wrap{width:260px;height:16px;border-radius:999px;background:rgba(255,255,255,.08);overflow:hidden;border:1px solid var(--line)}
    .progress{height:100%;width:0%;background:linear-gradient(90deg,var(--accent3),var(--accent2),var(--accent1))}
    .question-card{padding:24px;margin-bottom:18px}
    .q-meta{display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap;color:var(--muted);font-size:.9rem;margin-bottom:10px}
    .stem{font-size:1.08rem;line-height:1.6;margin-bottom:16px}
    .scenario{background:rgba(255,255,255,.05);padding:14px;border-radius:16px;border:1px solid var(--line);margin-bottom:16px;color:#efeaff}
    .options{display:grid;gap:12px}
    .option-row{align-items:flex-start;gap:12px;padding:12px 14px;border-radius:14px;background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.08)}
    .option-row input{margin-top:4px}
    .hint-box{margin-top:16px;padding:12px 14px;border-radius:14px;background:rgba(58,166,255,.1);border:1px solid rgba(58,166,255,.25);display:none}
    .hint-box.show{display:block}
    .table-grid{flex-direction:column;gap:10px}
    .table-row{display:grid;grid-template-columns:1.4fr 1fr 1fr 1fr;gap:8px;align-items:stretch}
    .table-head div,.table-cell{padding:12px;border-radius:12px;border:1px solid var(--line);background:rgba(255,255,255,.04)}
    .table-head div{font-weight:700;background:rgba(255,255,255,.09)}
    .drag-bank,.drop-area{display:grid;gap:10px}
    .drag-bank{grid-template-columns:repeat(auto-fit,minmax(150px,1fr));margin-bottom:14px}
    .drag-chip{padding:12px;border-radius:14px;background:linear-gradient(90deg,rgba(143,92,255,.25),rgba(255,138,31,.22));border:1px solid var(--line);cursor:grab;text-align:center;font-weight:700}
    .drop-area{grid-template-columns:1fr}
    .drop-row{align-items:center;justify-content:space-between;gap:10px;background:rgba(255,255,255,.04);border:1px solid var(--line);padding:10px;border-radius:14px}
    .drop-slot{min-height:48px;min-width:180px;padding:10px;border:2px dashed rgba(255,255,255,.25);border-radius:12px;display:flex;align-items:center;justify-content:center;color:var(--muted);background:rgba(0,0,0,.18)}
    .drop-slot.filled{border-style:solid;color:white;background:rgba(58,166,255,.14)}
    .controls{justify-content:space-between;gap:12px;flex-wrap:wrap;margin-top:18px}
    .question-nav{gap:8px;flex-wrap:wrap;margin:16px 0 22px}
    .nav-dot{width:42px;height:42px;border-radius:12px;border:1px solid var(--line);background:rgba(255,255,255,.05);color:var(--text);font-weight:700}
    .nav-dot.active{background:linear-gradient(90deg,var(--accent2),var(--accent1))}
    .nav-dot.done{outline:2px solid rgba(50,209,124,.7)}
    .results-grid{display:grid;grid-template-columns:1fr 1fr;gap:20px}
    .result-big{font-size:3rem;font-weight:900;margin:0}
    .pass{color:var(--good)}
    .fail{color:var(--bad)}
    .certificate{padding:34px;background:linear-gradient(180deg,rgba(143,92,255,.22),rgba(255,138,31,.16),rgba(58,166,255,.15));text-align:center;border:3px solid rgba(255,255,255,.16)}
    .certificate h2{font-size:2.1rem;margin-bottom:8px}
    .cert-name{font-size:2rem;font-weight:900;color:#fff2d5;margin:18px 0}
    .ribbon{display:inline-block;padding:10px 18px;border-radius:999px;background:linear-gradient(90deg,var(--accent1),var(--accent2));font-weight:800;margin-bottom:14px}
    .footer-note{margin-top:20px;color:var(--muted);font-size:.86rem}
    .center{text-align:center}
    @media print{
      body *{visibility:hidden}
      #certificateScreen, #certificateScreen *{visibility:visible}
      #certificateScreen{position:absolute;left:0;top:0;width:100%;padding:0;margin:0;background:white;color:black}
      .no-print{display:none!important}
      .certificate{box-shadow:none;border:4px solid #333;color:black;background:white}
    }
    @media (max-width:920px){
      .hero,.results-grid{grid-template-columns:1fr}
      .table-row{grid-template-columns:1fr}
    }
  </style>
</head>
<body class="block-copy">
  <div class="app">
    <section id="startScreen" class="screen active">
      <div class="hero">
        <div class="panel">
          <h1>Mission Matter</h1>
          <p class="sub">Welcome to your Grade 8 Science EOG-style challenge. Take your time, read every scenario carefully, and use evidence from what you know about atoms, the periodic table, and matter. You can do hard things.</p>
          <div class="message-box">
            <strong>Encouragement:</strong> Think like a scientist. Look for patterns, compare evidence, and choose the answer you can defend.
          </div>
          <div class="front-grid">
            <div>
              <label for="studentName"><strong>Enter your full name</strong></label>
              <div class="name-box">
                <input id="studentName" type="text" placeholder="Type your name here" autocomplete="off" />
                <button class="primary" id="beginBtn">Start Challenge</button>
              </div>
            </div>
            <div class="tiny">25 questions • 100 points total • Score 75% or higher to unlock a certificate.</div>
          </div>
        </div>
        <div class="panel periodic-panel">
          <h2 style="margin-bottom:0">Periodic Table Quick Reference</h2>
          <div class="tiny">Use this reference on page one before you begin. Pay attention to groups, periods, metals, metalloids, nonmetals, and noble gases.</div>
          <div class="legend">
            <span class="pill metal">Metal</span>
            <span class="pill metalloid">Metalloid</span>
            <span class="pill nonmetal">Nonmetal</span>
            <span class="pill noble">Noble Gas</span>
          </div>
          <div class="periodic-wrap">
            <div id="periodicTable" class="periodic-table"></div>
          </div>
        </div>
      </div>
    </section>

    <section id="quizScreen" class="screen">
      <div class="topbar panel">
        <div>
          <h2 style="margin-bottom:6px">Mission Matter Assessment</h2>
          <div class="tiny">Student: <span id="displayName">Scientist</span></div>
        </div>
        <div class="score-bar">
          <div><strong>Answered:</strong> <span id="answeredCount">0</span>/25</div>
          <div class="progress-wrap"><div id="progressBar" class="progress"></div></div>
          <div><strong>Current Page:</strong> <span id="pageNum">1</span>/25</div>
        </div>
      </div>
      <div id="questionNav" class="question-nav"></div>
      <div id="questionContainer"></div>
    </section>

    <section id="resultScreen" class="screen">
      <div class="results-grid">
        <div class="panel">
          <h2>Results</h2>
          <p class="result-big" id="scorePercent">0%</p>
          <p id="passFailText"></p>
          <p id="scoreBreakdown"></p>
          <div class="controls no-print">
            <button class="secondary" id="reviewBtn">Review Answers</button>
            <button class="primary" id="certBtn">View Certificate</button>
            <button class="tertiary" id="restartBtn">Restart</button>
          </div>
        </div>
        <div class="panel">
          <h3>Skills Included</h3>
          <ul>
            <li>Periodic table patterns and properties</li>
            <li>Protons, neutrons, electrons, and neutral atoms</li>
            <li>Elements, compounds, homogeneous mixtures, and heterogeneous mixtures</li>
            <li>Physical vs. chemical changes</li>
            <li>Conservation of mass and particle rearrangement</li>
          </ul>
          <p class="tiny">This game blocks copy and paste to keep the challenge honest and focused.</p>
        </div>
      </div>
    </section>

    <section id="certificateScreen" class="screen">
      <div class="certificate">
        <div class="ribbon">Science Mastery Certificate</div>
        <h2>Certificate of Achievement</h2>
        <p>This certifies that</p>
        <div class="cert-name" id="certName">Student Name</div>
        <p>successfully completed the <strong>Mission Matter Grade 8 Science Challenge</strong></p>
        <p>with a score of <strong id="certScore">0%</strong></p>
        <p id="certStatusLine">demonstrating strong scientific reasoning and problem-solving.</p>
        <p style="margin-top:28px">Awarded on <span id="certDate"></span></p>
        <div style="margin-top:38px;display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap">
          <div style="flex:1;min-width:200px">
            <div style="border-top:2px solid rgba(255,255,255,.45);padding-top:8px">Student Signature</div>
          </div>
          <div style="flex:1;min-width:200px">
            <div style="border-top:2px solid rgba(255,255,255,.45);padding-top:8px">Science Teacher</div>
          </div>
        </div>
      </div>
      <div class="controls no-print" style="margin-top:18px">
        <button class="secondary" id="backResultsBtn">Back to Results</button>
        <button class="primary" onclick="window.print()">Print Certificate</button>
      </div>
    </section>
  </div>

  <script>
    const periodicData = [
      {n:1,s:'H',c:'nonmetal',p:1,g:1},{n:2,s:'He',c:'noble',p:1,g:18},
      {n:3,s:'Li',c:'metal',p:2,g:1},{n:4,s:'Be',c:'metal',p:2,g:2},{n:5,s:'B',c:'metalloid',p:2,g:13},{n:6,s:'C',c:'nonmetal',p:2,g:14},{n:7,s:'N',c:'nonmetal',p:2,g:15},{n:8,s:'O',c:'nonmetal',p:2,g:16},{n:9,s:'F',c:'nonmetal',p:2,g:17},{n:10,s:'Ne',c:'noble',p:2,g:18},
      {n:11,s:'Na',c:'metal',p:3,g:1},{n:12,s:'Mg',c:'metal',p:3,g:2},{n:13,s:'Al',c:'metal',p:3,g:13},{n:14,s:'Si',c:'metalloid',p:3,g:14},{n:15,s:'P',c:'nonmetal',p:3,g:15},{n:16,s:'S',c:'nonmetal',p:3,g:16},{n:17,s:'Cl',c:'nonmetal',p:3,g:17},{n:18,s:'Ar',c:'noble',p:3,g:18},
      {n:19,s:'K',c:'metal',p:4,g:1},{n:20,s:'Ca',c:'metal',p:4,g:2},{n:21,s:'Sc',c:'metal',p:4,g:3},{n:22,s:'Ti',c:'metal',p:4,g:4},{n:23,s:'V',c:'metal',p:4,g:5},{n:24,s:'Cr',c:'metal',p:4,g:6},{n:25,s:'Mn',c:'metal',p:4,g:7},{n:26,s:'Fe',c:'metal',p:4,g:8},{n:27,s:'Co',c:'metal',p:4,g:9},{n:28,s:'Ni',c:'metal',p:4,g:10},{n:29,s:'Cu',c:'metal',p:4,g:11},{n:30,s:'Zn',c:'metal',p:4,g:12},{n:31,s:'Ga',c:'metal',p:4,g:13},{n:32,s:'Ge',c:'metalloid',p:4,g:14},{n:33,s:'As',c:'metalloid',p:4,g:15},{n:34,s:'Se',c:'nonmetal',p:4,g:16},{n:35,s:'Br',c:'nonmetal',p:4,g:17},{n:36,s:'Kr',c:'noble',p:4,g:18}
    ];

    const questions = [
      {
        type:'mcq',
        standard:'PS.8.1.1',
        dok:'DOK 3',
        stem:'A science team studies four samples from the cafeteria. Which sample should be classified as a compound?',
        scenario:'Sample A contains only iron atoms. Sample B contains water molecules. Sample C contains salt crystals mixed with pepper flakes. Sample D contains air in a balloon.',
        options:[
          'Sample A, because it has one type of atom only',
          'Sample B, because it contains more than one type of atom chemically bonded',
          'Sample C, because two substances are together in one container',
          'Sample D, because gases always form compounds'
        ],
        answer:'Sample B, because it contains more than one type of atom chemically bonded',
        hint:'A compound is a pure substance made of two or more different atoms bonded together.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.1',
        dok:'DOK 3',
        stem:'A student says trail mix is a homogeneous mixture because it is one snack. Which claim best challenges that statement?',
        scenario:'The trail mix contains raisins, pretzels, peanuts, and chocolate candies that can be seen separately.',
        options:[
          'The claim is wrong because trail mix is made of atoms',
          'The claim is wrong because the parts are not evenly distributed throughout the sample',
          'The claim is correct because all mixtures are homogeneous',
          'The claim is correct because food cannot be heterogeneous'
        ],
        answer:'The claim is wrong because the parts are not evenly distributed throughout the sample',
        hint:'Heterogeneous mixtures have visibly different parts.'
      },
      {
        type:'table',
        standard:'PS.8.1.2',
        dok:'DOK 3',
        stem:'Complete the table for a neutral atom of magnesium. Use the periodic table information shown on the front page and the mass number given here.',
        scenario:'Magnesium has atomic number 12 and mass number 24.',
        rows:[{label:'Protons',key:'p'},{label:'Electrons',key:'e'},{label:'Neutrons',key:'n'}],
        answers:{p:'12',e:'12',n:'12'},
        hint:'For a neutral atom: protons = electrons. Neutrons = mass number − atomic number.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.2',
        dok:'DOK 3',
        stem:'Which statement best explains why two atoms with different numbers of protons must be different elements?',
        scenario:'A class compares one atom with 6 protons to another atom with 8 protons.',
        options:[
          'The number of protons determines the identity of the element',
          'The number of neutrons determines whether atoms are solids or liquids',
          'Atoms with more electrons are always metals',
          'Only mass number matters when naming an element'
        ],
        answer:'The number of protons determines the identity of the element',
        hint:'Atomic number equals the number of protons.'
      },
      {
        type:'dragdrop',
        standard:'PS.8.1.2',
        dok:'DOK 3',
        stem:'Drag each subatomic particle to its best description.',
        scenario:'Use what you know about charge and location in a neutral atom.',
        bank:['Proton','Neutron','Electron'],
        targets:[
          {label:'Positive charge in the nucleus',answer:'Proton'},
          {label:'No charge in the nucleus',answer:'Neutron'},
          {label:'Negative charge outside the nucleus',answer:'Electron'}
        ],
        hint:'Only electrons are outside the nucleus.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.3',
        dok:'DOK 3',
        stem:'A student must choose an element for electrical wiring. Which element location on the periodic table gives the best evidence the student should choose a metal such as copper?',
        scenario:'The student needs a material that is shiny, bendable, and a good conductor of electricity.',
        options:[
          'An element in the nonmetal region on the right side',
          'An element in the noble gas group because those are stable',
          'An element in the metal region because metals are generally conductive and malleable',
          'Any element in group 18 because all gases conduct well'
        ],
        answer:'An element in the metal region because metals are generally conductive and malleable',
        hint:'Connect location on the periodic table to predicted properties.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.3',
        dok:'DOK 4',
        stem:'A scientist describes an unknown element as a dull gas that rarely reacts with other substances. Where is the element most likely located on the periodic table?',
        scenario:'The scientist is using physical and chemical properties to predict placement without knowing the element name.',
        options:[
          'In group 1 with the highly reactive alkali metals',
          'Near group 18 with the noble gases',
          'In the transition metals because they are all gases',
          'Along the zigzag metalloid line because metalloids are nonreactive gases'
        ],
        answer:'Near group 18 with the noble gases',
        hint:'Noble gases are known for very low reactivity.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.4',
        dok:'DOK 3',
        stem:'Which change is best classified as a chemical change?',
        scenario:'A student records four observations during lab stations.',
        options:[
          'Ice cubes melting into liquid water',
          'A paper towel being torn into pieces',
          'A shiny nail forming reddish-brown rust after several days',
          'Sugar dissolving into hot tea'
        ],
        answer:'A shiny nail forming reddish-brown rust after several days',
        hint:'Chemical changes create new substances and often show evidence such as color change, gas, or precipitate.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.4',
        dok:'DOK 4',
        stem:'A teacher mixes two clear liquids. The mixture becomes cloudy and a solid forms at the bottom while the beaker feels warmer. Which conclusion is best supported?',
        scenario:'Students must use multiple pieces of evidence rather than only one clue.',
        options:[
          'A physical change occurred because the liquids remained clear',
          'A chemical change occurred because a precipitate formed and energy was released',
          'A physical change occurred because temperature can change anytime',
          'No change occurred because both reactants were liquids'
        ],
        answer:'A chemical change occurred because a precipitate formed and energy was released',
        hint:'Look for more than one sign of a chemical reaction.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.4',
        dok:'DOK 3',
        stem:'Which classroom example is the best evidence of a physical change rather than a chemical change?',
        scenario:'Students compare several changes in matter during a review game.',
        options:[
          'A tablet bubbling in water and producing gas',
          'Milk souring after being left out',
          'Copper wire being bent into a coil',
          'Wood burning and producing ash'
        ],
        answer:'Copper wire being bent into a coil',
        hint:'A physical change changes form, shape, or state but not composition.'
      },
      {
        type:'multi',
        standard:'PS.8.1.5',
        dok:'DOK 4',
        stem:'Select the two statements that best explain the law of conservation of mass during a chemical reaction.',
        scenario:'Students are evaluating a particle model of a reaction in a sealed container.',
        options:[
          'The total number of each type of atom remains the same before and after the reaction',
          'Atoms disappear when energy is released',
          'Atoms are rearranged into new substances',
          'Products always weigh less than reactants',
          'Only liquids follow the law of conservation of mass'
        ],
        answers:[
          'The total number of each type of atom remains the same before and after the reaction',
          'Atoms are rearranged into new substances'
        ],
        hint:'Matter is conserved because atoms are not created or destroyed in ordinary chemical reactions.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.5',
        dok:'DOK 3',
        stem:'Which equation is balanced?',
        scenario:'Students compare several symbolic models of chemical reactions.',
        options:[
          'H2 + O2 → H2O',
          '2H2 + O2 → 2H2O',
          'Na + Cl2 → NaCl',
          'Mg + O2 → MgO'
        ],
        answer:'2H2 + O2 → 2H2O',
        hint:'Count atoms of each element on both sides.'
      },
      {
        type:'dragdrop',
        standard:'PS.8.1.5',
        dok:'DOK 4',
        stem:'Drag each description to the correct matter category.',
        scenario:'Each card describes particles in a sample. Sort carefully.',
        bank:['Only one type of atom is present','Different atoms are chemically bonded','Different particles are mixed evenly','Different particles are mixed unevenly'],
        targets:[
          {label:'Element',answer:'Only one type of atom is present'},
          {label:'Compound',answer:'Different atoms are chemically bonded'},
          {label:'Homogeneous mixture',answer:'Different particles are mixed evenly'},
          {label:'Heterogeneous mixture',answer:'Different particles are mixed unevenly'}
        ],
        hint:'Watch the words bonded, evenly, and unevenly.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.3',
        dok:'DOK 3',
        stem:'Why are sodium (Na) and potassium (K) expected to have similar chemical properties?',
        scenario:'A student notices the two elements are in the same column on the periodic table.',
        options:[
          'They are both in the same group, and elements in a group tend to share properties',
          'They have the same atomic mass',
          'They are both gases at room temperature',
          'They are both noble gases'
        ],
        answer:'They are both in the same group, and elements in a group tend to share properties',
        hint:'Groups are vertical columns.'
      },
      {
        type:'table',
        standard:'PS.8.1.1',
        dok:'DOK 4',
        stem:'Classify each substance. Type the best category in the table: element, compound, homogeneous mixture, or heterogeneous mixture.',
        scenario:'Use composition and particle arrangement, not just appearance.',
        rows:[
          {label:'Aluminum foil',key:'a'},
          {label:'Salt water',key:'b'},
          {label:'Chocolate chip cookie',key:'c'}
        ],
        answers:{a:'element',b:'homogeneous mixture',c:'heterogeneous mixture'},
        hint:'A pure metal is an element. A solution is homogeneous. Visible parts usually mean heterogeneous.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.2',
        dok:'DOK 3',
        stem:'A neutral fluorine atom has 9 protons. How many electrons does it have?',
        scenario:'The question focuses on neutral atoms only.',
        options:['7','8','9','18'],
        answer:'9',
        hint:'Neutral means total positive and negative charges balance.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.3',
        dok:'DOK 4',
        stem:'Which prediction about bromine (Br) is most reasonable based on its location near other nonmetals on the periodic table?',
        scenario:'A student has not learned every property of bromine but can reason from patterns.',
        options:[
          'It is likely shiny, malleable, and highly conductive',
          'It is likely more similar to chlorine than to calcium',
          'It is likely a noble gas that does not form compounds',
          'It is likely placed with alkali metals because it reacts with water'
        ],
        answer:'It is likely more similar to chlorine than to calcium',
        hint:'Use nearby elements and group patterns.'
      },
      {
        type:'multi',
        standard:'PS.8.1.4',
        dok:'DOK 4',
        stem:'Select the two observations that provide the strongest evidence that a chemical reaction occurred.',
        scenario:'Students are reviewing data from several lab groups.',
        options:[
          'The sample changed from a liquid to a solid after freezing',
          'A gas bubbled out of the mixture',
          'A new solid formed from two liquids',
          'The sample was cut into smaller pieces',
          'The beaker was moved to another table'
        ],
        answers:['A gas bubbled out of the mixture','A new solid formed from two liquids'],
        hint:'Evidence of a chemical change includes gas production and precipitate formation.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.5',
        dok:'DOK 4',
        stem:'A student weighs reactants in a closed container before a reaction and then weighs the sealed container after the reaction. What result should the student expect?',
        scenario:'The reaction produces a gas, but the container remains sealed the entire time.',
        options:[
          'The final mass should be lower because gas always escapes',
          'The final mass should be higher because new substances formed',
          'The final mass should stay the same because matter is conserved in the closed system',
          'The final mass cannot be predicted'
        ],
        answer:'The final mass should stay the same because matter is conserved in the closed system',
        hint:'Closed systems keep matter from escaping.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.1',
        dok:'DOK 3',
        stem:'A student filters muddy water. The water collected below the filter is clearer than the original sample. What conclusion is best supported?',
        scenario:'The student is deciding whether the original sample was a compound or mixture.',
        options:[
          'The original sample was a compound because compounds separate by filtration',
          'The original sample was a mixture because physical methods can separate mixtures',
          'The original sample was an element because elements dissolve in water',
          'The original sample was a compound because a new substance formed'
        ],
        answer:'The original sample was a mixture because physical methods can separate mixtures',
        hint:'Filtration is a physical separation method.'
      },
      {
        type:'dragdrop',
        standard:'PS.8.1.4',
        dok:'DOK 3',
        stem:'Drag each change to the correct category.',
        scenario:'Each example describes a change in matter.',
        bank:['Burning a marshmallow','Melting candle wax','Rusting a bicycle chain','Crushing a soda can'],
        targets:[
          {label:'Physical change',answer:'Melting candle wax'},
          {label:'Physical change',answer:'Crushing a soda can'},
          {label:'Chemical change',answer:'Burning a marshmallow'},
          {label:'Chemical change',answer:'Rusting a bicycle chain'}
        ],
        hint:'Some drag categories can have more than one correct card.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.2',
        dok:'DOK 4',
        stem:'A model of a neutral atom shows 17 protons, 18 neutrons, and 17 electrons. Which conclusion is best supported?',
        scenario:'Students must reason about identity and neutrality from the model.',
        options:[
          'The atom is neutral and its identity depends on the 17 protons',
          'The atom is not neutral because neutrons outnumber electrons',
          'The atom must be magnesium because it has 18 neutrons',
          'The atom is positively charged because protons and electrons are equal'
        ],
        answer:'The atom is neutral and its identity depends on the 17 protons',
        hint:'Element identity comes from proton count, not neutron count.'
      },
      {
        type:'table',
        standard:'PS.8.1.3',
        dok:'DOK 4',
        stem:'Use periodic table patterns to complete the table with metal, nonmetal, metalloid, or noble gas.',
        scenario:'Classify each element by its general location and properties.',
        rows:[
          {label:'Neon (Ne)',key:'ne'},
          {label:'Silicon (Si)',key:'si'},
          {label:'Calcium (Ca)',key:'ca'}
        ],
        answers:{ne:'noble gas',si:'metalloid',ca:'metal'},
        hint:'Neon is in group 18. Silicon sits on the zigzag line. Calcium is on the left side.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.5',
        dok:'DOK 4',
        stem:'Which explanation best describes why the equation 2Mg + O2 → 2MgO follows the law of conservation of mass?',
        scenario:'A student must use coefficients and subscripts correctly.',
        options:[
          'There are two magnesium atoms and two oxygen atoms on each side of the equation',
          'The equation has arrows, so it must be balanced',
          'The products contain fewer atoms because compounds are denser',
          'Oxygen does not count because it is a gas'
        ],
        answer:'There are two magnesium atoms and two oxygen atoms on each side of the equation',
        hint:'Count the atoms, not just the formulas.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.1',
        dok:'DOK 4',
        stem:'A teacher shows four particle diagrams. Which diagram would represent a homogeneous mixture?',
        scenario:'Diagram A shows only identical single atoms. Diagram B shows bonded pairs of two different atoms only. Diagram C shows two different particles spread evenly throughout. Diagram D shows large clumps of one particle separated from another.',
        options:[
          'Diagram A',
          'Diagram B',
          'Diagram C',
          'Diagram D'
        ],
        answer:'Diagram C',
        hint:'A homogeneous mixture contains more than one particle type distributed evenly.'
      },
      {
        type:'mcq',
        standard:'PS.8.1.4',
        dok:'DOK 4',
        stem:'During a lab, one group claims that dissolving sugar in water is a chemical change because the sugar seems to disappear. Which response best evaluates that claim?',
        scenario:'Students can recover the sugar by evaporating the water.',
        options:[
          'The claim is correct because invisible substances are always new substances',
          'The claim is incorrect because the sugar can be recovered by a physical process, showing no new substance formed',
          'The claim is correct because all solutions involve reactions',
          'The claim is incorrect because water cannot mix with solids'
        ],
        answer:'The claim is incorrect because the sugar can be recovered by a physical process, showing no new substance formed',
        hint:'If a substance can be recovered without changing its identity, the change is physical.'
      }
    ];

    const state = {
      studentName:'',
      current:0,
      answers:{},
      score:0,
      submitted:false
    };

    const el = id => document.getElementById(id);

    function buildPeriodicTable(){
      const wrap = el('periodicTable');
      for(let p=1;p<=4;p++){
        for(let g=1;g<=18;g++){
          const found = periodicData.find(item=>item.p===p && item.g===g);
          const cell = document.createElement('div');
          if(found){
            cell.className = `el ${found.c}`;
            cell.innerHTML = `<small>${found.n}</small><span>${found.s}</span>`;
            cell.title = `${found.s} (#${found.n})`;
          } else {
            cell.className='blank';
          }
          wrap.appendChild(cell);
        }
      }
    }

    function showScreen(screenId){
      document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
      el(screenId).classList.add('active');
      window.scrollTo({top:0,behavior:'smooth'});
    }

    function updateProgress(){
      const answered = Object.keys(state.answers).length;
      el('answeredCount').textContent = answered;
      el('pageNum').textContent = state.current + 1;
      el('progressBar').style.width = `${(answered/questions.length)*100}%`;
      renderNav();
    }

    function renderNav(){
      const nav = el('questionNav');
      nav.innerHTML='';
      questions.forEach((q,i)=>{
        const btn = document.createElement('button');
        btn.className = 'nav-dot' + (i===state.current?' active':'') + (state.answers[i]!==undefined?' done':'');
        btn.textContent = i+1;
        btn.onclick = ()=>{state.current=i; renderQuestion();};
        nav.appendChild(btn);
      });
    }

    function makeHint(q){
      return `<div class="hint-box" id="hintBox">${q.hint}</div><div style="margin-top:14px"><button class="secondary" type="button" id="hintBtn">Show Hint</button></div>`;
    }

    function renderQuestion(){
      updateProgress();
      const q = questions[state.current];
      const saved = state.answers[state.current];
      let html = `
        <div class="question-card">
          <div class="q-meta"><span><strong>Question ${state.current+1}</strong></span><span>${q.standard}</span><span>${q.dok}</span></div>
          <div class="scenario">${q.scenario}</div>
          <div class="stem">${q.stem}</div>
      `;

      if(q.type==='mcq'){
        html += `<div class="options">`;
        q.options.forEach((opt,idx)=>{
          html += `<label class="option-row"><input type="radio" name="q${state.current}" value="${escapeHtml(opt)}" ${saved===opt?'checked':''}> <span><strong>${String.fromCharCode(65+idx)}.</strong> ${opt}</span></label>`;
        });
        html += `</div>`;
      }

      if(q.type==='multi'){
        html += `<div class="options">`;
        q.options.forEach((opt,idx)=>{
          const checked = Array.isArray(saved) && saved.includes(opt) ? 'checked' : '';
          html += `<label class="option-row"><input type="checkbox" value="${escapeHtml(opt)}" ${checked}> <span><strong>${String.fromCharCode(65+idx)}.</strong> ${opt}</span></label>`;
        });
        html += `</div>`;
      }

      if(q.type==='table'){
        html += `<div class="table-grid"><div class="table-row table-head"><div>Category</div><div>Student Answer</div><div></div><div></div></div>`;
        q.rows.forEach(r=>{
          const val = saved && saved[r.key] ? saved[r.key] : '';
          html += `<div class="table-row"><div class="table-cell">${r.label}</div><div class="table-cell"><input type="text" data-key="${r.key}" value="${escapeHtml(val)}" placeholder="Type answer"></div><div class="table-cell tiny">Use lowercase or standard science words.</div><div class="table-cell"></div></div>`;
        });
        html += `</div>`;
      }

      if(q.type==='dragdrop'){
        html += `<div class="drag-bank" id="dragBank">`;
        q.bank.forEach((item,idx)=>{
          html += `<div class="drag-chip" draggable="true" data-item="${escapeHtml(item)}" id="drag-${state.current}-${idx}">${item}</div>`;
        });
        html += `</div><div class="drop-area">`;
        q.targets.forEach((t,idx)=>{
          const slotValue = saved && saved[idx] ? saved[idx] : '';
          html += `<div class="drop-row"><div><strong>${t.label}</strong></div><div class="drop-slot ${slotValue ? 'filled' : ''}" data-target-index="${idx}">${slotValue || 'Drop here'}</div></div>`;
        });
        html += `</div>`;
      }

      html += makeHint(q);
      html += `
        <div class="controls">
          <button class="secondary" id="prevBtn" ${state.current===0?'disabled':''}>Previous</button>
          <div style="display:flex;gap:10px;flex-wrap:wrap">
            <button class="secondary" id="saveBtn">Save Answer</button>
            ${state.current===questions.length-1 ? '<button class="primary" id="submitBtn">Submit Quiz</button>' : '<button class="primary" id="nextBtn">Next</button>'}
          </div>
        </div>
      </div>`;

      el('questionContainer').innerHTML = html;
      bindQuestionEvents(q);
    }

    function bindQuestionEvents(q){
      const hintBtn = el('hintBtn');
      const hintBox = el('hintBox');
      hintBtn.onclick = ()=> hintBox.classList.toggle('show');

      const prevBtn = el('prevBtn');
      if(prevBtn) prevBtn.onclick = ()=>{saveCurrent(); state.current--; renderQuestion();};

      const nextBtn = el('nextBtn');
      if(nextBtn) nextBtn.onclick = ()=>{saveCurrent(); state.current++; renderQuestion();};

      const saveBtn = el('saveBtn');
      saveBtn.onclick = ()=>{saveCurrent(); updateProgress();};

      const submitBtn = el('submitBtn');
      if(submitBtn) submitBtn.onclick = ()=>{saveCurrent(); submitQuiz();};

      if(q.type==='dragdrop'){
        document.querySelectorAll('.drag-chip').forEach(chip=>{
          chip.addEventListener('dragstart', e=>{
            e.dataTransfer.setData('text/plain', chip.dataset.item);
          });
        });
        document.querySelectorAll('.drop-slot').forEach(slot=>{
          slot.addEventListener('dragover', e=> e.preventDefault());
          slot.addEventListener('drop', e=>{
            e.preventDefault();
            const val = e.dataTransfer.getData('text/plain');
            slot.textContent = val;
            slot.classList.add('filled');
          });
          slot.addEventListener('click', ()=>{
            if(slot.classList.contains('filled')){
              slot.textContent='Drop here';
              slot.classList.remove('filled');
            }
          });
        });
      }
    }

    function normalize(str){
      return String(str || '').trim().toLowerCase().replace(/\s+/g,' ');
    }

    function saveCurrent(){
      const q = questions[state.current];
      if(q.type==='mcq'){
        const checked = document.querySelector(`input[name="q${state.current}"]:checked`);
        if(checked) state.answers[state.current] = checked.value;
      }
      if(q.type==='multi'){
        const picks = [...document.querySelectorAll('#questionContainer input[type="checkbox"]:checked')].map(x=>x.value);
        if(picks.length) state.answers[state.current] = picks;
      }
      if(q.type==='table'){
        const obj = {};
        document.querySelectorAll('#questionContainer input[data-key]').forEach(inp=> obj[inp.dataset.key] = inp.value);
        state.answers[state.current] = obj;
      }
      if(q.type==='dragdrop'){
        const obj = {};
        document.querySelectorAll('.drop-slot').forEach(slot=>{
          const idx = slot.dataset.targetIndex;
          if(slot.classList.contains('filled')) obj[idx] = slot.textContent;
        });
        state.answers[state.current] = obj;
      }
      updateProgress();
    }

    function isCorrect(q, saved){
      if(saved===undefined) return false;
      if(q.type==='mcq') return normalize(saved)===normalize(q.answer);
      if(q.type==='multi'){
        const a = (saved||[]).map(normalize).sort();
        const b = (q.answers||[]).map(normalize).sort();
        return JSON.stringify(a)===JSON.stringify(b);
      }
      if(q.type==='table'){
        return Object.keys(q.answers).every(k=>normalize(saved[k])===normalize(q.answers[k]));
      }
      if(q.type==='dragdrop'){
        const usedTargets = {};
        q.targets.forEach((t,idx)=>{
          if(!usedTargets[t.label]) usedTargets[t.label] = [];
          usedTargets[t.label].push({idx, answer:t.answer});
        });
        return q.targets.every((t,idx)=> normalize(saved[idx])===normalize(t.answer));
      }
      return false;
    }

    function submitQuiz(){
      let correct = 0;
      questions.forEach((q,idx)=>{
        if(isCorrect(q,state.answers[idx])) correct++;
      });
      state.score = Math.round((correct / questions.length) * 100);
      el('scorePercent').textContent = `${state.score}%`;
      const passed = state.score >= 75;
      el('passFailText').innerHTML = passed
        ? `<span class="pass"><strong>Excellent work!</strong> You earned the certificate.</span>`
        : `<span class="fail"><strong>Keep growing.</strong> Review the questions and try again.</span>`;
      el('scoreBreakdown').textContent = `You answered ${correct} out of ${questions.length} questions correctly.`;
      el('certBtn').style.display = passed ? 'inline-block' : 'none';
      prepareCertificate(passed);
      showScreen('resultScreen');
    }

    function prepareCertificate(passed){
      el('certName').textContent = state.studentName || 'Student';
      el('certScore').textContent = `${state.score}%`;
      el('certStatusLine').textContent = passed
        ? 'demonstrating strong scientific reasoning and problem-solving.'
        : 'and is encouraged to keep practicing scientific reasoning skills.';
      el('certDate').textContent = new Date().toLocaleDateString();
    }

    function escapeHtml(str){
      return String(str)
        .replace(/&/g,'&amp;')
        .replace(/</g,'&lt;')
        .replace(/>/g,'&gt;')
        .replace(/"/g,'&quot;')
        .replace(/'/g,'&#039;');
    }

    function restartQuiz(){
      state.current = 0;
      state.answers = {};
      state.score = 0;
      state.studentName = '';
      el('studentName').value = '';
      showScreen('startScreen');
    }

    document.addEventListener('copy', e=>e.preventDefault());
    document.addEventListener('paste', e=>e.preventDefault());
    document.addEventListener('cut', e=>e.preventDefault());
    document.addEventListener('contextmenu', e=>e.preventDefault());
    document.addEventListener('keydown', e=>{
      const blocked = (e.ctrlKey || e.metaKey) && ['c','v','x','a','p','s'].includes(e.key.toLowerCase());
      if(blocked) e.preventDefault();
    });

    el('beginBtn').onclick = ()=>{
      const name = el('studentName').value.trim();
      if(!name){
        alert('Please enter your name before starting.');
        return;
      }
      state.studentName = name;
      el('displayName').textContent = name;
      showScreen('quizScreen');
      renderQuestion();
    };

    el('reviewBtn').onclick = ()=>{ state.current = 0; showScreen('quizScreen'); renderQuestion(); };
    el('certBtn').onclick = ()=> showScreen('certificateScreen');
    el('restartBtn').onclick = restartQuiz;
    el('backResultsBtn').onclick = ()=> showScreen('resultScreen');

    buildPeriodicTable();
  </script>
</body>
</html>
