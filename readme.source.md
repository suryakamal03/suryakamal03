```aura width=800 height=620
<div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'flex-start', width: '100%', height: '100%', background: 'linear-gradient(180deg, #0b0b10 0%, #08080d 100%)', borderRadius: 20, overflow: 'hidden', fontFamily: 'Inter, sans-serif', paddingTop: 56 }}>
  <svg width="800" height="620" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="hg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(108,195,130,0.45)" />
        <stop offset="100%" stopColor="rgba(108,195,130,0)" />
      </radialGradient>
      <radialGradient id="hg2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(230,100,115,0.42)" />
        <stop offset="100%" stopColor="rgba(230,100,115,0)" />
      </radialGradient>
      <radialGradient id="hg3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(195,155,255,0.3)" />
        <stop offset="100%" stopColor="rgba(195,155,255,0)" />
      </radialGradient>
      <radialGradient id="hg4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,195,110,0.22)" />
        <stop offset="100%" stopColor="rgba(255,195,110,0)" />
      </radialGradient>
      <radialGradient id="hg5" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(80,160,220,0.24)" />
        <stop offset="100%" stopColor="rgba(80,160,220,0)" />
      </radialGradient>
    </defs>
    <ellipse cx="110" cy="560" rx="260" ry="200" fill="url(#hg1)" />
    <ellipse cx="710" cy="70" rx="230" ry="190" fill="url(#hg2)" />
    <ellipse cx="620" cy="580" rx="200" ry="160" fill="url(#hg3)" />
    <ellipse cx="200" cy="55" rx="190" ry="150" fill="url(#hg4)" />
    <ellipse cx="400" cy="590" rx="170" ry="130" fill="url(#hg5)" />
  </svg>

  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 10 }}>
    <span style={{ fontSize: 56, fontWeight: 700, color: '#ffffff', letterSpacing: -2, lineHeight: 1 }}>SURYA K</span>
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
        <a href="https://www.linkedin.com/in/surya-kamal-369954306/" style={{ textDecoration: 'none' }}><span style={{ padding: '9px 16px', background: 'rgba(255,255,255,0.06)', color: '#ffffff', borderRadius: 999, fontSize: 12, border: '1px solid rgba(255,255,255,0.12)', letterSpacing: 0.5 }}>LinkedIn / suryakamal3</span></a>
        <a href="https://www.suryakamal.dev/" style={{ textDecoration: 'none' }}><span style={{ padding: '9px 16px', background: 'rgba(255,255,255,0.06)', color: '#ffffff', borderRadius: 999, fontSize: 12, border: '1px solid rgba(255,255,255,0.12)', letterSpacing: 0.5 }}>Portfolio / suryakamal.dev</span></a>
        <a href="mailto:professionalsurya3@gmail.com" style={{ textDecoration: 'none' }}><span style={{ padding: '9px 16px', background: 'rgba(255,255,255,0.06)', color: '#ffffff', borderRadius: 999, fontSize: 12, border: '1px solid rgba(255,255,255,0.12)', letterSpacing: 0.5 }}>Email / professionalsurya3@gmail.com</span></a>
      </div>
    </div>
  </div>
</div>
```

## Connections

- [LinkedIn / suryakamal3](https://www.linkedin.com/in/surya-kamal-369954306/)
- [Portfolio / suryakamal.dev](https://www.suryakamal.dev/)
- [Email / professionalsurya3@gmail.com](mailto:professionalsurya3@gmail.com)