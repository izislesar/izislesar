```aura width=800 height=220
<div style={{
  display: 'flex',
  flexDirection: 'column',
  alignItems: 'center',
  justifyContent: 'center',
  width: '100%',
  height: '100%',
  background: 'linear-gradient(135deg, #1e1e2e 0%, #181825 60%, #11111b 100%)',
  borderRadius: '16px',
  border: '1px solid #313244',
  gap: '18px',
  position: 'relative',
  overflow: 'hidden',
}}>
  <div style={{
    display: 'flex',
    position: 'absolute',
    top: '0', left: '0', right: '0', height: '3px',
    background: 'linear-gradient(90deg, #89b4fa 0%, #cba6f7 50%, #f38ba8 100%)',
  }} />

  <div style={{
    display: 'flex', position: 'absolute', top: '-55px', right: '-55px',
    width: '210px', height: '210px', borderRadius: '50%',
    background: 'radial-gradient(circle, rgba(137,180,250,0.10) 0%, transparent 72%)',
  }} />

  <div style={{ display: 'flex', alignItems: 'center', gap: '20px' }}>
    <div style={{
      display: 'flex', width: '82px', height: '82px', borderRadius: '50%',
      background: 'linear-gradient(135deg, #89b4fa, #cba6f7, #f38ba8)',
      alignItems: 'center', justifyContent: 'center',
    }}>
      <div style={{
        display: 'flex', width: '76px', height: '76px', borderRadius: '50%',
        overflow: 'hidden', border: '2px solid #1e1e2e',
      }}>
        <img src="https://github.com/izislesar.png" style={{ width: '76px', height: '76px' }} />
      </div>
    </div>

    <div style={{ display: 'flex', flexDirection: 'column', gap: '5px' }}>
      <span style={{ fontSize: '40px', fontWeight: '700', color: '#cdd6f4', letterSpacing: '-1px' }}>
        izislesar
      </span>
      <span style={{ fontSize: '14px', color: '#89b4fa', fontWeight: '600', letterSpacing: '1.4px', textTransform: 'uppercase' }}>
        systems · backend · networking
      </span>
    </div>
  </div>

  <div style={{ display: 'flex', gap: '8px' }}>
    {[
      { tag: 'go',       bg: 'rgba(137,180,250,0.12)', border: '#89b4fa', color: '#89b4fa' },
      { tag: 'arch',     bg: 'rgba(166,227,161,0.12)', border: '#a6e3a1', color: '#a6e3a1' },
      { tag: 'docker',   bg: 'rgba(249,226,175,0.12)', border: '#f9e2af', color: '#f9e2af' },
      { tag: 'ebpf',     bg: 'rgba(203,166,247,0.12)', border: '#cba6f7', color: '#cba6f7' },
      { tag: 'postgres', bg: 'rgba(243,139,168,0.12)', border: '#f38ba8', color: '#f38ba8' },
    ].map(({ tag, bg, border, color }) => (
      <div key={tag} style={{
        display: 'flex', padding: '4px 13px', borderRadius: '999px',
        background: bg, border: `1px solid ${border}`, color: color,
        fontSize: '12px', fontWeight: '700', letterSpacing: '0.8px', textTransform: 'uppercase',
      }}>
        {tag}
      </div>
    ))}
  </div>
</div>
```

```aura width=800 height=150
<div style={{
  display: 'flex', alignItems: 'stretch', width: '100%', height: '100%',
  background: '#1e1e2e', borderRadius: '16px', border: '1px solid #313244', overflow: 'hidden',
}}>
  {[
    { label: 'goback',    value: 'backup utility',      color: '#a6e3a1', accent: '#a6e3a1' },
    { label: 'spcase',    value: 'go / postgres app',   color: '#89b4fa', accent: '#89b4fa' },
    { label: 'xray-core', value: 'network research',    color: '#cba6f7', accent: '#cba6f7' },
    { label: 'focus',     value: 'linux · infra · ebpf', color: '#f38ba8', accent: '#f38ba8' },
  ].map((item, i) => (
    <div key={i} style={{
      display: 'flex', flex: '1', flexDirection: 'column', alignItems: 'center', justifyContent: 'center', gap: '8px',
      borderRight: i < 3 ? '1px solid #313244' : 'none', position: 'relative', overflow: 'hidden',
    }}>
      <div style={{
        display: 'flex', position: 'absolute', bottom: '0', left: '20%', right: '20%', height: '2px',
        background: item.accent, borderRadius: '2px', opacity: '0.65',
      }} />
      <span style={{ fontSize: '11px', color: '#6c7086', fontWeight: '700', letterSpacing: '1.2px', textTransform: 'uppercase' }}>
        {item.label}
      </span>
      <span style={{ fontSize: '13px', color: item.color, fontWeight: '600', letterSpacing: '0.2px' }}>
        {item.value}
      </span>
    </div>
  ))}
</div>
```

[![GitHub Stats](https://ghstats.dev/api/card?username=izislesar&theme=catppuccin&hide=trend%2Cavg%2Cactive_day%2Cgrade%2Ccontributions%2Crepos%2Cfollowers&custom_title=Stats&border_radius=10)](https://github.com/izislesar)
