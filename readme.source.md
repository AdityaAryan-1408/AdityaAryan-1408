
<!-- Aditya Aryan — readme-aura profile
     Edit this file, then run: npx readme-aura build
     GitHub Actions can regenerate README.md when this source changes.
-->

```aura width=1100 height=300
<div style={{
  width: '100%', height: '100%', position: 'relative', overflow: 'hidden',
  display: 'flex', flexDirection: 'column', justifyContent: 'center',
  padding: '42px 48px', boxSizing: 'border-box',
  background: '#0b0d10', border: '1px solid #242a31', borderRadius: 18,
  fontFamily: 'Inter, sans-serif'
}}>
  <style>{`
    @keyframes drift-a { 0%,100% { transform: translate(0,0); opacity:.24; } 50% { transform: translate(24px,-15px); opacity:.42; } }
    @keyframes drift-b { 0%,100% { transform: translate(0,0); opacity:.18; } 50% { transform: translate(-20px,14px); opacity:.34; } }
    @keyframes orbit { from { transform: rotate(0deg); } to { transform: rotate(360deg); } }
    #aura-glow-a { animation: drift-a 11s ease-in-out infinite; }
    #aura-glow-b { animation: drift-b 13s ease-in-out infinite; }
    #aura-orbit { animation: orbit 38s linear infinite; transform-origin: 910px 150px; }
  `}</style>
  <svg width="1100" height="300" style={{position:'absolute',top:0,left:0}}>
    <defs>
      <radialGradient id="aura-grad-a"><stop offset="0%" stopColor="rgba(116,156,190,0.34)"/><stop offset="100%" stopColor="rgba(116,156,190,0)"/></radialGradient>
      <radialGradient id="aura-grad-b"><stop offset="0%" stopColor="rgba(160,177,190,0.20)"/><stop offset="100%" stopColor="rgba(160,177,190,0)"/></radialGradient>
    </defs>
    <ellipse id="aura-glow-a" cx="1010" cy="30" rx="260" ry="190" fill="url(#aura-grad-a)"/>
    <ellipse id="aura-glow-b" cx="790" cy="300" rx="230" ry="160" fill="url(#aura-grad-b)"/>
    <g id="aura-orbit" fill="none" stroke="rgba(190,205,218,0.12)" strokeWidth="1">
      <circle cx="910" cy="150" r="56"/><circle cx="910" cy="150" r="94"/><circle cx="910" cy="150" r="132"/>
      <circle cx="910" cy="94" r="3" fill="#a8bac9" stroke="none"/>
    </g>
  </svg>
  <div style={{display:'flex',flexDirection:'column',position:'relative',zIndex:2}}>
    <div style={{display:'flex',alignItems:'center',gap:10,marginBottom:20}}>
      <div style={{width:7,height:7,borderRadius:7,background:'#91b7a2'}}/>
      <span style={{fontSize:12,color:'#91b7a2',letterSpacing:2.5,fontWeight:600}}>DEVELOPER · INDIA</span>
    </div>
    <span style={{fontSize:48,fontWeight:750,color:'#f2f4f6',letterSpacing:-1.8,lineHeight:1.08}}>Aditya Aryan</span>
    <span style={{fontSize:18,color:'#b5c0ca',marginTop:13,fontWeight:500}}>Software Developer / Generative AI</span>
    <span style={{fontSize:13,color:'#7f8b96',marginTop:13}}>Building useful software, intelligent systems and developer tools.</span>
    <div style={{display:'flex',gap:9,marginTop:25}}>
      <a href="https://aditya-aryan-portfolio.vercel.app/" style={{textDecoration:'none',display:'flex',padding:'8px 14px',borderRadius:8,background:'#e8edf1',color:'#111820',fontSize:11,fontWeight:700}}>PORTFOLIO ↗</a>
      <a href="https://www.linkedin.com/in/aryanaditya1408/" style={{textDecoration:'none',display:'flex',padding:'8px 14px',borderRadius:8,border:'1px solid #3b4650',color:'#d1d9df',fontSize:11,fontWeight:600}}>LINKEDIN ↗</a>
      <a href="https://github.com/AdityaAryan-1408" style={{textDecoration:'none',display:'flex',padding:'8px 14px',borderRadius:8,border:'1px solid #3b4650',color:'#d1d9df',fontSize:11,fontWeight:600}}>GITHUB ↗</a>
    </div>
  </div>
</div>
```

## About

I'm an MCA student at **NIT Jamshedpur**, based in India, working across web development, backend engineering and Generative AI.

I enjoy turning ideas into scalable applications, automating workflows, and building production-minded systems that solve practical problems. My current learning focus is Go, agentic AI, RAG architectures and reliable deployment.

```aura width=860 height=156
<div style={{width:'100%',height:'100%',display:'flex',gap:12,fontFamily:'Inter, sans-serif'}}>
  <div style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:14,padding:'19px 20px',display:'flex',flexDirection:'column',justifyContent:'space-between'}}>
    <span style={{fontSize:10,color:'#84919c',letterSpacing:2,fontWeight:700}}>EDUCATION</span>
    <div style={{display:'flex',flexDirection:'column',gap:5}}>
      <span style={{fontSize:19,color:'#edf1f4',fontWeight:700}}>MCA</span>
      <span style={{fontSize:12,color:'#a7b2bc'}}>NIT Jamshedpur</span>
    </div>
    <span style={{fontSize:10,color:'#65717c'}}>Computer Applications</span>
  </div>
  <div style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:14,padding:'19px 20px',display:'flex',flexDirection:'column',justifyContent:'space-between'}}>
    <span style={{fontSize:10,color:'#84919c',letterSpacing:2,fontWeight:700}}>ENGINEERING</span>
    <div style={{display:'flex',flexDirection:'column',gap:5}}>
      <span style={{fontSize:19,color:'#edf1f4',fontWeight:700}}>Backend + AI</span>
      <span style={{fontSize:12,color:'#a7b2bc'}}>APIs · RAG · LLM workflows</span>
    </div>
    <span style={{fontSize:10,color:'#65717c'}}>From prototype to production</span>
  </div>
  <div style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:14,padding:'19px 20px',display:'flex',flexDirection:'column',justifyContent:'space-between'}}>
    <span style={{fontSize:10,color:'#84919c',letterSpacing:2,fontWeight:700}}>CURRENTLY LEARNING</span>
    <div style={{display:'flex',flexDirection:'column',gap:5}}>
      <span style={{fontSize:19,color:'#edf1f4',fontWeight:700}}>Go + Agents</span>
      <span style={{fontSize:12,color:'#a7b2bc'}}>Concurrency · Harnesses</span>
    </div>
    <span style={{fontSize:10,color:'#65717c'}}>Systems that scale</span>
  </div>
</div>
```

## Selected Projects

```aura width=860 height=350
<div style={{width:'100%',height:'100%',display:'flex',flexDirection:'column',gap:10,fontFamily:'Inter, sans-serif'}}>
  <div style={{display:'flex',gap:10,flex:1}}>
    <div style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:13,padding:'17px 18px',display:'flex',flexDirection:'column',justifyContent:'space-between'}}>
      <div style={{display:'flex',justifyContent:'space-between',alignItems:'center'}}>
        <span style={{fontSize:10,color:'#91b7a2',letterSpacing:1.5,fontWeight:700}}>DESKTOP · PRODUCTIVITY</span>
        <span style={{fontSize:11,color:'#65717c'}}>01</span>
      </div>
      <div style={{display:'flex',flexDirection:'column',gap:6}}>
        <span style={{fontSize:23,color:'#edf1f4',fontWeight:700}}>Ollumi</span>
        <span style={{fontSize:12,color:'#9aa6b1',lineHeight:1.5}}>A Windows productivity suite with a smart notch, dashboard, clipboard, file shelf and system monitoring.</span>
      </div>
      <span style={{fontSize:10,color:'#84919c'}}>Tauri · Rust · React</span>
    </div>
    <div style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:13,padding:'17px 18px',display:'flex',flexDirection:'column',justifyContent:'space-between'}}>
      <div style={{display:'flex',justifyContent:'space-between',alignItems:'center'}}>
        <span style={{fontSize:10,color:'#91b7a2',letterSpacing:1.5,fontWeight:700}}>GENERATIVE AI</span>
        <span style={{fontSize:11,color:'#65717c'}}>02</span>
      </div>
      <div style={{display:'flex',flexDirection:'column',gap:6}}>
        <span style={{fontSize:23,color:'#edf1f4',fontWeight:700}}>PrepBuddy</span>
        <span style={{fontSize:12,color:'#9aa6b1',lineHeight:1.5}}>Voice-based AI interview practice with generated questions and personalized feedback.</span>
      </div>
      <span style={{fontSize:10,color:'#84919c'}}>Next.js · Gemini · Vapi · Firebase</span>
    </div>
  </div>
  <div style={{display:'flex',gap:10,flex:1}}>
    <div style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:13,padding:'17px 18px',display:'flex',flexDirection:'column',justifyContent:'space-between'}}>
      <div style={{display:'flex',justifyContent:'space-between',alignItems:'center'}}>
        <span style={{fontSize:10,color:'#91b7a2',letterSpacing:1.5,fontWeight:700}}>REPOSITORY INTELLIGENCE</span>
        <span style={{fontSize:11,color:'#65717c'}}>03</span>
      </div>
      <div style={{display:'flex',flexDirection:'column',gap:6}}>
        <span style={{fontSize:23,color:'#edf1f4',fontWeight:700}}>RepoReader AI</span>
        <span style={{fontSize:12,color:'#9aa6b1',lineHeight:1.5}}>GitHub repository ingestion and question-answering with retrieval-augmented generation.</span>
      </div>
      <span style={{fontSize:10,color:'#84919c'}}>RAG · Supabase pgvector</span>
    </div>
    <div style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:13,padding:'17px 18px',display:'flex',flexDirection:'column',justifyContent:'space-between'}}>
      <div style={{display:'flex',justifyContent:'space-between',alignItems:'center'}}>
        <span style={{fontSize:10,color:'#91b7a2',letterSpacing:1.5,fontWeight:700}}>FULL-STACK · REAL-TIME</span>
        <span style={{fontSize:11,color:'#65717c'}}>04</span>
      </div>
      <div style={{display:'flex',flexDirection:'column',gap:6}}>
        <span style={{fontSize:23,color:'#edf1f4',fontWeight:700}}>FetchQuest</span>
        <span style={{fontSize:12,color:'#9aa6b1',lineHeight:1.5}}>A peer-to-peer campus micro-economy app with real-time communication and secure user flows.</span>
      </div>
      <span style={{fontSize:10,color:'#84919c'}}>React · Node.js · MongoDB · Socket.IO</span>
    </div>
  </div>
</div>
```

## Technology

```aura width=860 height=310
<div style={{width:'100%',height:'100%',display:'flex',flexDirection:'column',gap:10,fontFamily:'Inter, sans-serif'}}>
  <div style={{display:'flex',gap:10,flex:1}}>
    <div style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:12,padding:'15px 16px',display:'flex',flexDirection:'column',gap:12}}>
      <span style={{fontSize:10,color:'#91b7a2',letterSpacing:1.6,fontWeight:700}}>LANGUAGES</span>
      <div style={{display:'flex',flexWrap:'wrap',alignContent:'flex-start',gap:7}}>
        {['Go','Java','C++','JavaScript','TypeScript','Python','SQL','C'].map(function(item) { return <span key={item} style={{fontSize:12,color:'#dce3e8',background:'#151a1f',border:'1px solid #2a333c',borderRadius:6,padding:'5px 8px'}}>{item}</span>; })}
      </div>
    </div>
    <div style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:12,padding:'15px 16px',display:'flex',flexDirection:'column',gap:12}}>
      <span style={{fontSize:10,color:'#91b7a2',letterSpacing:1.6,fontWeight:700}}>FRAMEWORKS</span>
      <div style={{display:'flex',flexWrap:'wrap',alignContent:'flex-start',gap:7}}>
        {['React','Next.js','Node.js','Express','Spring','Hibernate','Tailwind CSS','Vite'].map(function(item) { return <span key={item} style={{fontSize:12,color:'#dce3e8',background:'#151a1f',border:'1px solid #2a333c',borderRadius:6,padding:'5px 8px'}}>{item}</span>; })}
      </div>
    </div>
  </div>
  <div style={{display:'flex',gap:10,flex:1}}>
    <div style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:12,padding:'15px 16px',display:'flex',flexDirection:'column',gap:12}}>
      <span style={{fontSize:10,color:'#91b7a2',letterSpacing:1.6,fontWeight:700}}>DATA & AI</span>
      <div style={{display:'flex',flexWrap:'wrap',alignContent:'flex-start',gap:7}}>
        {['PostgreSQL','MySQL','MongoDB','Redis','Supabase','Firebase','RAG','LLMs','Vector Search'].map(function(item) { return <span key={item} style={{fontSize:12,color:'#dce3e8',background:'#151a1f',border:'1px solid #2a333c',borderRadius:6,padding:'5px 8px'}}>{item}</span>; })}
      </div>
    </div>
    <div style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:12,padding:'15px 16px',display:'flex',flexDirection:'column',gap:12}}>
      <span style={{fontSize:10,color:'#91b7a2',letterSpacing:1.6,fontWeight:700}}>TOOLS & INFRA</span>
      <div style={{display:'flex',flexWrap:'wrap',alignContent:'flex-start',gap:7}}>
        {['Git','GitHub Actions','Docker','Nginx','Maven','JWT','Vercel','Render'].map(function(item) { return <span key={item} style={{fontSize:12,color:'#dce3e8',background:'#151a1f',border:'1px solid #2a333c',borderRadius:6,padding:'5px 8px'}}>{item}</span>; })}
      </div>
    </div>
  </div>
</div>
```

## Current Focus

- **Go backend engineering** — concurrency, networking, APIs and system design.
- **Agentic AI** — multi-agent systems, tool use and orchestration.
- **AI harness engineering** — building reliable execution environments around AI agents.
- **RAG & LLM systems** — retrieval pipelines, evaluation and practical integrations.
- **DevOps** — containerization, CI/CD, deployment and observability.

## GitHub Activity

```aura width=860 height=156
(function() {
  var stats = [
    {label:'PUBLIC REPOSITORIES', value:String((github && github.stats && github.stats.totalRepos) || 0)},
    {label:'STARS EARNED', value:String((github && github.stats && github.stats.totalStars) || 0)},
    {label:'COMMITS', value:String((github && github.stats && github.stats.totalCommits) || 0)}
  ];
  return <div style={{width:'100%',height:'100%',display:'flex',gap:10,fontFamily:'Inter, sans-serif'}}>
    {stats.map(function(item) {
      return <div key={item.label} style={{flex:1,background:'#0b0d10',border:'1px solid #242a31',borderRadius:13,display:'flex',flexDirection:'column',justifyContent:'center',alignItems:'center',gap:9}}>
        <span style={{fontSize:30,fontWeight:750,color:'#e7edf1'}}>{item.value}</span>
        <span style={{fontSize:9,color:'#84919c',letterSpacing:1.4,fontWeight:700}}>{item.label}</span>
      </div>;
    })}
  </div>;
})()
```

```aura width=860 height=260
<div style={{width:'100%',height:'100%',background:'#0b0d10',border:'1px solid #242a31',borderRadius:14,padding:12,display:'flex',flexDirection:'column',gap:8,boxSizing:'border-box'}}>
  <div style={{display:'flex',justifyContent:'space-between',alignItems:'center',padding:'2px 5px'}}>
    <span style={{fontSize:11,color:'#dce3e8',fontWeight:700,letterSpacing:1}}>CONTRIBUTION ACTIVITY</span>
    <span style={{fontSize:10,color:'#84919c'}}>AdityaAryan-1408</span>
  </div>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AdityaAryan-1408&bg_color=0b0d10&color=aab7c4&line=91b7a2&point=e7edf1&area=true&hide_border=true" width="100%" height="205" style={{objectFit:'contain'}}/>
</div>
```

## Connect

- **Portfolio:** [aditya-aryan-portfolio.vercel.app](https://aditya-aryan-portfolio.vercel.app/)
- **LinkedIn:** [linkedin.com/in/aryanaditya1408](https://www.linkedin.com/in/aryanaditya1408/)
- **X:** [@AdityaAryan1408](https://x.com/AdityaAryan1408)
- **GitHub:** [@AdityaAryan-1408](https://github.com/AdityaAryan-1408)

---

<p align="center">
  <sub>Designed with readme-aura · Built with curiosity and shipped with purpose.</sub>
</p>
