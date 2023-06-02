# Headless とは

Headless software (e.g. "headless Java"[1] or "headless Linux",[2]) is software capable of working on a device without a graphical user interface. Such software receives inputs and provides output through other interfaces like network or serial port and is common on servers and embedded devices.

- Headless CMS
- Headless UI Library
- Headless BPO SaaS

## Headless な UI Library

- https://headlessui.com/ 
- https://tanstack.com/table/v8 

Style は提供せず、ロジックのみを提供する

cf) MUI や ant-design などのつらみ<br>
そのまま使えるメリットがあったが細かいデザインを当てる際に辛くなってしまった。<br>
デザイン実装をできる & React の設計もできる人が必要だった<br>

## 実装例

これまでのフロントエンドを UI 部分と、ロジックの部分に分割できる

https://codesandbox.io/s/zuv0bd?file=/src/main.tsx 
https://headlessui.com/react/popover#closing-popovers-manually
