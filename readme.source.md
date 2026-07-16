```aura width=800 height=620
<div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'flex-start', width: '100%', height: '100%', background: '#08080d', borderRadius: 20, overflow: 'hidden', fontFamily: 'Inter, sans-serif', paddingTop: 48 }}>
  <style>{`
    @keyframes orb-a { 0%, 100% { transform: translate(0, 0); opacity: 0.6; } 50% { transform: translate(28px, -22px); opacity: 0.9; } }
    @keyframes orb-b { 0%, 100% { transform: translate(0, 0); opacity: 0.5; } 50% { transform: translate(-22px, 18px); opacity: 0.75; } }
    @keyframes orb-c { 0%, 100% { transform: translate(0, 0); opacity: 0.35; } 50% { transform: translate(16px, -28px); opacity: 0.6; } }
    @keyframes ring-blink { 0%, 100% { opacity: 0.06; } 50% { opacity: 0.18; } }
    @keyframes ring-blink-b { 0%, 100% { opacity: 0.04; } 50% { opacity: 0.12; } }
    @keyframes dot-spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
    #hero-o1 { animation: orb-a 9s ease-in-out infinite; }
    #hero-o2 { animation: orb-b 11s ease-in-out infinite 0.8s; }
    #hero-o3 { animation: orb-a 8s ease-in-out infinite 2s; }
    #hero-o4 { animation: orb-b 13s ease-in-out infinite 0.4s; }
    #hero-o5 { animation: orb-c 7s ease-in-out infinite 1.2s; }
    #hr1 { animation: ring-blink 8s ease-in-out infinite; }
    #hr2 { animation: ring-blink 8s ease-in-out infinite 1.4s; }
    #hr3 { animation: ring-blink-b 8s ease-in-out infinite 2.8s; }
    #hr4 { animation: ring-blink-b 8s ease-in-out infinite 4.2s; }
    #hr5 { animation: ring-blink-b 10s ease-in-out infinite 5.6s; }
    #hero-dot { animation: dot-spin 20s linear infinite; }
  `}</style>

  <svg width="800" height="620" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="hg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(108,195,130,0.55)" />
        <stop offset="100%" stopColor="rgba(108,195,130,0)" />
      </radialGradient>
      <radialGradient id="hg2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(230,100,115,0.5)" />
        <stop offset="100%" stopColor="rgba(230,100,115,0)" />
      </radialGradient>
      <radialGradient id="hg3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(195,155,255,0.35)" />
        <stop offset="100%" stopColor="rgba(195,155,255,0)" />
      </radialGradient>
      <radialGradient id="hg4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,195,110,0.28)" />
        <stop offset="100%" stopColor="rgba(255,195,110,0)" />
      </radialGradient>
      <radialGradient id="hg5" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(80,160,220,0.3)" />
        <stop offset="100%" stopColor="rgba(80,160,220,0)" />
      </radialGradient>
    </defs>
    <ellipse id="hero-o1" cx="110" cy="560" rx="260" ry="200" fill="url(#hg1)" />
    <ellipse id="hero-o2" cx="710" cy="70" rx="230" ry="190" fill="url(#hg2)" />
    <ellipse id="hero-o3" cx="620" cy="580" rx="200" ry="160" fill="url(#hg3)" />
    <ellipse id="hero-o4" cx="200" cy="55" rx="190" ry="150" fill="url(#hg4)" />
    <ellipse id="hero-o5" cx="400" cy="590" rx="170" ry="130" fill="url(#hg5)" />
    <circle id="hr1" cx="400" cy="150" r="52" fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.7" />
    <circle id="hr2" cx="400" cy="150" r="92" fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.7" />
    <circle id="hr3" cx="400" cy="150" r="138" fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.7" />
    <circle id="hr4" cx="400" cy="150" r="192" fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.7" />
    <circle id="hr5" cx="400" cy="150" r="256" fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.7" />
    <g id="hero-dot">
      <circle cx="400" cy="98" r="2.5" fill="rgba(255,255,255,0.5)" />
    </g>
  </svg>

  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 10 }}>
    <span style={{ fontSize: 56, fontWeight: 700, color: '#ffffff', letterSpacing: -2, lineHeight: 1 }}>{(github && github.user && (github.user.name || github.user.login)) || 'SURYA K'}</span>
    <span style={{ fontSize: 13, color: 'rgba(255,255,255,0.4)', marginTop: 14, letterSpacing: 5, textTransform: 'uppercase', fontWeight: 300 }}>design · code · create</span>

    <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: 34, maxWidth: 560, textAlign: 'center' }}>
      <span style={{ fontSize: 11, color: 'rgba(255,255,255,0.35)', letterSpacing: 3, textTransform: 'uppercase', marginBottom: 10 }}>about</span>
      <span style={{ fontSize: 18, fontWeight: 500, color: 'rgba(255,255,255,0.85)', lineHeight: 1.6 }}>I'm a self-taught programmer.</span>
      <span style={{ fontSize: 18, fontWeight: 500, color: 'rgba(255,255,255,0.85)', lineHeight: 1.6 }}>I like solving problems by building projects.</span>
      <span style={{ fontSize: 14, color: 'rgba(255,255,255,0.5)', marginTop: 10, lineHeight: 1.5 }}>Currently pursuing MCA, and building <b>Bundle</b>, a new SaaS platform. Check it out.</span>
    </div>

    <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: 36 }}>
      <span style={{ fontSize: 11, color: 'rgba(255,255,255,0.3)', letterSpacing: 4, textTransform: 'uppercase', marginBottom: 16 }}>stack</span>
      <div style={{ display: 'flex', flexWrap: 'wrap', gap: 10, justifyContent: 'center', maxWidth: 620 }}>
        {(github && github.languages && github.languages.length > 0
          ? github.languages.slice(0, 10).map(function(l) { return l.name; })
          : ['React', 'Next.js', 'TypeScript', 'Node.js', 'PostgreSQL', 'Supabase', 'Rust', 'Tauri', 'Kotlin', 'Android']
        ).map((tech, i) => (
          <span key={i} style={{ padding: '7px 18px', background: 'rgba(255,255,255,0.04)', color: 'rgba(255,255,255,0.65)', borderRadius: 100, fontSize: 12, border: '1px solid rgba(255,255,255,0.08)', letterSpacing: 0.5 }}>{tech}</span>
        ))}
      </div>
    </div>

    <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', marginTop: 30 }}>
      <span style={{ fontSize: 11, color: 'rgba(255,255,255,0.3)', letterSpacing: 4, textTransform: 'uppercase', marginBottom: 14 }}>connection</span>
      <div style={{ display: 'flex', flexWrap: 'wrap', gap: 10, justifyContent: 'center' }}>
        <a href="https://github.com/suryakamal03" style={{ textDecoration: 'none' }}><span style={{ padding: '9px 16px', background: 'rgba(255,255,255,0.06)', color: '#ffffff', borderRadius: 999, fontSize: 12, border: '1px solid rgba(255,255,255,0.12)', letterSpacing: 0.5 }}>GitHub</span></a>
        <a href="https://www.linkedin.com/in/surya-kamal-369954306/" style={{ textDecoration: 'none' }}><span style={{ padding: '9px 16px', background: 'rgba(255,255,255,0.06)', color: '#ffffff', borderRadius: 999, fontSize: 12, border: '1px solid rgba(255,255,255,0.12)', letterSpacing: 0.5 }}>LinkedIn</span></a>
        <a href="https://www.suryakamal.dev/" style={{ textDecoration: 'none' }}><span style={{ padding: '9px 16px', background: 'rgba(255,255,255,0.06)', color: '#ffffff', borderRadius: 999, fontSize: 12, border: '1px solid rgba(255,255,255,0.12)', letterSpacing: 0.5 }}>Portfolio</span></a>
        <a href="mailto:professionalsurya3@gmail.com" style={{ textDecoration: 'none' }}><span style={{ padding: '9px 16px', background: 'rgba(255,255,255,0.06)', color: '#ffffff', borderRadius: 999, fontSize: 12, border: '1px solid rgba(255,255,255,0.12)', letterSpacing: 0.5 }}>Email</span></a>
      </div>
    </div>
  </div>
</div>
```