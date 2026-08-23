```aura width=800 height=190
<div style={{
  display: 'flex',
  width: '100%',
  height: '100%',
  alignItems: 'center',
  justifyContent: 'space-between',
  padding: '34px 42px',
  background: '#0b0f0c',
  border: '1px solid #263229',
  borderRadius: '12px',
  position: 'relative',
  overflow: 'hidden',
  fontFamily: 'Inter',
}}>
  <div style={{
    display: 'flex',
    position: 'absolute',
    left: '0',
    top: '0',
    bottom: '0',
    width: '4px',
    background: '#56d364',
  }} />

  <div style={{ display: 'flex', flexDirection: 'column', gap: '10px' }}>
    <span style={{
      color: '#e6eee8',
      fontSize: '42px',
      fontWeight: '700',
      letterSpacing: '-1.4px',
    }}>
      izislesar
    </span>
    <span style={{
      color: '#9aac9d',
      fontSize: '16px',
      fontWeight: '500',
      letterSpacing: '-0.1px',
    }}>
      Backend · Infrastructure · Networking
    </span>
    <span style={{
      color: '#6e7f72',
      fontSize: '13px',
      fontWeight: '500',
    }}>
      Go engineer working close to Linux and the network stack.
    </span>
  </div>

  <div style={{
    display: 'flex',
    width: '86px',
    height: '86px',
    borderRadius: '10px',
    overflow: 'hidden',
    border: '1px solid #31563a',
    background: '#101612',
  }}>
    <img src="https://github.com/izislesar.png" style={{ width: '86px', height: '86px' }} />
  </div>
</div>
```

```aura width=800 height=250
<div style={{
  display: 'flex',
  width: '100%',
  height: '100%',
  padding: '28px 32px',
  background: '#0b0f0c',
  border: '1px solid #263229',
  borderRadius: '12px',
  flexDirection: 'column',
  gap: '20px',
  fontFamily: 'Inter',
}}>
  <span style={{
    color: '#d8e2da',
    fontSize: '15px',
    fontWeight: '650',
  }}>
    Engineering
  </span>

  <div style={{ display: 'flex', flexDirection: 'column', gap: '13px' }}>
    {[
      ['Backend', 'Go · REST APIs · PostgreSQL'],
      ['Infrastructure', 'Docker · Linux · systemd · GitHub Actions'],
      ['Networking', 'Xray / VLESS · nftables · eBPF'],
      ['Systems', 'Btrfs · process supervision · observability'],
    ].map(([label, value]) => (
      <div key={label} style={{
        display: 'flex',
        alignItems: 'center',
        minHeight: '32px',
      }}>
        <div style={{
          display: 'flex',
          width: '145px',
          color: '#56d364',
          fontSize: '13px',
          fontWeight: '650',
        }}>
          {label}
        </div>
        <div style={{
          display: 'flex',
          flex: '1',
          color: '#a8b5aa',
          fontSize: '13px',
          fontWeight: '500',
          paddingBottom: '8px',
          borderBottom: '1px solid #1d2820',
        }}>
          {value}
        </div>
      </div>
    ))}
  </div>
</div>
```

```aura width=800 height=96
<div style={{
  display: 'flex',
  width: '100%',
  height: '100%',
  background: '#0b0f0c',
  border: '1px solid #263229',
  borderRadius: '12px',
  overflow: 'hidden',
  fontFamily: 'Inter',
}}>
  {[
    ['Email', 'your@email.tld'],
    ['Telegram', '@username'],
  ].map(([label, value], i) => (
    <div key={label} style={{
      display: 'flex',
      flex: '1',
      flexDirection: 'column',
      justifyContent: 'center',
      padding: '0 28px',
      gap: '6px',
      borderRight: i === 0 ? '1px solid #263229' : 'none',
    }}>
      <span style={{ color: '#6e7f72', fontSize: '11px', fontWeight: '650', letterSpacing: '0.8px' }}>{label}</span>
      <span style={{ color: '#b7c3b9', fontSize: '13px', fontWeight: '550' }}>{value}</span>
    </div>
  ))}
</div>
```

[![GitHub activity](https://github-readme-activity-graph.vercel.app/graph?username=izislesar&bg_color=0b0f0c&color=9aac9d&line=56d364&point=7ee787&area=true&area_color=173d23&hide_border=true&custom_title=GitHub%20activity)](https://github.com/izislesar)

[![GitHub stats](https://github-readme-stats.vercel.app/api?username=izislesar&show_icons=true&hide_border=true&bg_color=0b0f0c&title_color=7ee787&text_color=9aac9d&icon_color=56d364&ring_color=56d364&include_all_commits=true&count_private=false&hide_rank=true)](https://github.com/izislesar)
