```aura width=800 height=250
<div style={{
  display: 'flex',
  width: '100%',
  height: '100%',
  background: 'linear-gradient(120deg, #07090d 0%, #0b0f16 58%, #111522 100%)',
  borderRadius: '10px',
  border: '1px solid #20283a',
  position: 'relative',
  overflow: 'hidden',
}}>
  <div style={{
    display: 'flex', position: 'absolute', top: '0', left: '0', right: '0', height: '2px',
    background: 'linear-gradient(90deg, #00e5ff 0%, #7c4dff 52%, #b388ff 100%)',
  }} />

  <div style={{
    display: 'flex', position: 'absolute', top: '-90px', right: '-40px', width: '320px', height: '320px',
    background: 'radial-gradient(circle, rgba(0,229,255,0.10) 0%, rgba(124,77,255,0.06) 32%, transparent 72%)',
    transform: 'rotate(-12deg)'
  }} />

  <div style={{
    display: 'flex', position: 'absolute', left: '25px', top: '30px', bottom: '30px', width: '4px',
    background: 'linear-gradient(180deg, #00e5ff 0%, #7c4dff 100%)',
  }} />

  <div style={{ display: 'flex', width: '100%', padding: '34px 42px 30px 54px', alignItems: 'center', justifyContent: 'space-between' }}>
    <div style={{ display: 'flex', flexDirection: 'column', gap: '14px', width: '510px' }}>
      <div style={{ display: 'flex', alignItems: 'center', gap: '14px' }}>
        <span style={{
          fontSize: '12px', color: '#00e5ff', fontWeight: '800', letterSpacing: '2.2px', textTransform: 'uppercase'
        }}>SYS::PROFILE</span>
        <span style={{ width: '58px', height: '1px', background: '#263046' }} />
        <span style={{ fontSize: '11px', color: '#667085', fontWeight: '700', letterSpacing: '1.4px' }}>ONLINE</span>
      </div>

      <span style={{
        fontSize: '48px', fontWeight: '800', color: '#eef4ff', letterSpacing: '-2.2px', lineHeight: '1'
      }}>izislesar</span>

      <span style={{
        fontSize: '14px', color: '#9aa4b2', fontWeight: '600', letterSpacing: '0.8px'
      }}>systems / backend / networking</span>

      <div style={{ display: 'flex', gap: '7px', marginTop: '3px' }}>
        {['GO','ARCH','POSTGRES','DOCKER','eBPF'].map((tag, i) => (
          <div key={tag} style={{
            display: 'flex', padding: '5px 10px',
            background: i % 2 === 0 ? '#0c1720' : '#111027',
            border: `1px solid ${i % 2 === 0 ? '#12394a' : '#30255d'}`,
            color: i % 2 === 0 ? '#63e6f5' : '#a78bfa',
            borderRadius: '4px', fontSize: '10px', fontWeight: '800', letterSpacing: '1px'
          }}>{tag}</div>
        ))}
      </div>
    </div>

    <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'flex-end', gap: '10px' }}>
      <div style={{
        display: 'flex', width: '118px', height: '118px', padding: '5px',
        background: 'linear-gradient(135deg, #00e5ff 0%, #7c4dff 100%)',
        clipPath: 'polygon(10% 0, 100% 0, 100% 90%, 90% 100%, 0 100%, 0 10%)'
      }}>
        <div style={{
          display: 'flex', width: '108px', height: '108px', overflow: 'hidden', background: '#080b11',
          clipPath: 'polygon(10% 0, 100% 0, 100% 90%, 90% 100%, 0 100%, 0 10%)'
        }}>
          <img src="https://github.com/izislesar.png" style={{ width: '108px', height: '108px' }} />
        </div>
      </div>
      <span style={{ fontSize: '10px', color: '#667085', fontWeight: '700', letterSpacing: '1.3px' }}>NODE_01 / ARCH</span>
    </div>
  </div>
</div>
```

```aura width=800 height=180
<div style={{
  display: 'flex', width: '100%', height: '100%',
  background: '#090c12', borderRadius: '10px', border: '1px solid #20283a', overflow: 'hidden'
}}>
  <div style={{ display: 'flex', flex: '1.15', flexDirection: 'column', padding: '24px 26px', borderRight: '1px solid #20283a', gap: '13px' }}>
    <span style={{ fontSize: '10px', color: '#00e5ff', fontWeight: '800', letterSpacing: '1.8px' }}>STACK</span>
    {[
      ['Go', '#00e5ff'], ['Linux / Arch', '#8b5cf6'], ['PostgreSQL', '#00e5ff'], ['Docker', '#8b5cf6']
    ].map(([label,color]) => (
      <div key={label} style={{ display: 'flex', alignItems: 'center', gap: '9px' }}>
        <span style={{ width: '5px', height: '5px', background: color }} />
        <span style={{ fontSize: '12px', color: '#cbd5e1', fontWeight: '650' }}>{label}</span>
      </div>
    ))}
  </div>

  <div style={{ display: 'flex', flex: '1.7', flexDirection: 'column', padding: '24px 26px', borderRight: '1px solid #20283a', gap: '11px' }}>
    <span style={{ fontSize: '10px', color: '#8b5cf6', fontWeight: '800', letterSpacing: '1.8px' }}>CURRENT WORK</span>
    <span style={{ fontSize: '13px', color: '#eef4ff', fontWeight: '750' }}>low-level network observability</span>
    <span style={{ fontSize: '12px', color: '#8a94a6', fontWeight: '600' }}>VPN infrastructure · eBPF · Linux tooling</span>
    <div style={{ display: 'flex', marginTop: '7px', gap: '6px' }}>
      {['goback','spcase','Xray-core'].map((name, i) => (
        <div key={name} style={{
          display: 'flex', padding: '4px 8px', borderRadius: '3px',
          border: `1px solid ${i === 1 ? '#25314a' : '#21374a'}`,
          background: '#0d121b', color: i === 1 ? '#a78bfa' : '#63e6f5',
          fontSize: '10px', fontWeight: '800', letterSpacing: '0.4px'
        }}>{name}</div>
      ))}
    </div>
  </div>

  <div style={{ display: 'flex', flex: '1', flexDirection: 'column', padding: '24px 24px', gap: '13px' }}>
    <span style={{ fontSize: '10px', color: '#00e5ff', fontWeight: '800', letterSpacing: '1.8px' }}>LINKS</span>
    <span style={{ fontSize: '12px', color: '#cbd5e1', fontWeight: '700' }}>github.com/izislesar</span>
    <span style={{ fontSize: '11px', color: '#7b8494', fontWeight: '600' }}>Go · Linux · Networking</span>
    <span style={{ fontSize: '11px', color: '#7b8494', fontWeight: '600' }}>production-minded systems</span>
  </div>
</div>
```

[![GitHub Stats](https://ghstats.dev/api/card?username=izislesar&theme=transparent&hide=trend%2Cavg%2Cactive_day%2Cgrade%2Ccontributions%2Crepos%2Cfollowers&custom_title=SYSTEM%20METRICS&border_radius=6)](https://github.com/izislesar)
