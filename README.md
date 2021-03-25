# sd202008-ansible

## 準備

### `textfsm` のインストール

```
pip install textfsm
```

### ntc-template のダウンロード

```
git clone https://github.com/networktocode/ntc-templates
```

これにより、Playbook から `ntc-templates/templates/cisco_ios_show_ip_ospf_neighbor.textfsm` のようなパスでファイルを参照できるようになる。

（`$ pip install ntc_templates` する方法もある。この場合は、`(略)/site-packages/ntc_templates/templates/cisco_ios_show_ip_ospf_neighbor.textfsm` というパスになる）
