```aura width=800 height=205
<div style={{
  display: 'flex', width: '100%', height: '100%',
  background: 'linear-gradient(135deg, #0b0f0c 0%, #0d120f 58%, #101612 100%)',
  borderRadius: '8px', border: '1px solid #263229', overflow: 'hidden',
  position: 'relative', fontFamily: 'monospace',
}}>
  <div style={{ display: 'flex', position: 'absolute', top: '0', left: '0', right: '0', height: '2px', background: '#56d364' }} />
  <div style={{ display: 'flex', position: 'absolute', right: '-70px', top: '-85px', width: '250px', height: '250px', borderRadius: '50%', background: 'radial-gradient(circle, rgba(126,231,135,0.08) 0%, transparent 68%)' }} />

  <div style={{ display: 'flex', width: '100%', alignItems: 'center', justifyContent: 'space-between', padding: '34px 42px' }}>
    <div style={{ display: 'flex', flexDirection: 'column', gap: '12px' }}>
      <span style={{ fontSize: '42px', color: '#e6eee8', fontWeight: '700', letterSpacing: '-1.8px' }}>izislesar</span>
      <span style={{ fontSize: '14px', color: '#9aac9d', fontWeight: '500', letterSpacing: '0.5px' }}>systems / backend / networking</span>
      <div style={{ display: 'flex', gap: '18px', marginTop: '5px' }}>
        <span style={{ fontSize: '11px', color: '#7ee787', fontWeight: '650' }}>Go</span>
        <span style={{ fontSize: '11px', color: '#7ee787', fontWeight: '650' }}>Linux</span>
        <span style={{ fontSize: '11px', color: '#7ee787', fontWeight: '650' }}>Networking</span>
      </div>
    </div>

    <div style={{ display: 'flex', width: '92px', height: '92px', border: '1px solid #334238', padding: '4px', background: '#0b0f0c' }}>
      <img src="https://github.com/izislesar.png" style={{ width: '84px', height: '84px' }} />
    </div>
  </div>
</div>
```

```aura width=800 height=96
<div style={{
  display: 'flex', width: '100%', height: '100%', background: '#0b0f0c',
  borderRadius: '8px', border: '1px solid #263229', overflow: 'hidden', fontFamily: 'monospace',
}}>
  {[
    { label: 'email', value: '—' },
    { label: 'telegram', value: '—' },
    { label: 'github', value: '@izislesar' },
  ].map((item, i) => (
    <div key={item.label} style={{
      display: 'flex', flex: '1', flexDirection: 'column', justifyContent: 'center',
      padding: '0 26px', gap: '7px', borderRight: i < 2 ? '1px solid #263229' : 'none'
    }}>
      <span style={{ fontSize: '10px', color: '#6e7f72', fontWeight: '700', letterSpacing: '1.1px', textTransform: 'uppercase' }}>{item.label}</span>
      <span style={{ fontSize: '13px', color: i === 2 ? '#7ee787' : '#c7d2c9', fontWeight: '600' }}>{item.value}</span>
    </div>
  ))}
</div>
```

[![GitHub activity](https://github-readme-activity-graph.vercel.app/graph?username=izislesar&bg_color=0b0f0c&color=9aac9d&line=56d364&point=7ee787&area=true&area_color=173d23&hide_border=true&custom_title=GitHub%20activity)](https://github.com/izislesar)

[![GitHub stats](https://github-readme-stats.vercel.app/api?username=izislesar&show_icons=true&hide_border=true&bg_color=0b0f0c&title_color=7ee787&text_color=9aac9d&icon_color=56d364&ring_color=56d364&include_all_commits=true&count_private=false&hide_rank=true)](https://github.com/izislesar)
