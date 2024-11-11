  \* { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: Arial, sans-serif; display: flex; align-items: center; justify-content: center; height: 100vh; background: #f0f2f5; color: #333; } .container { text-align: center; padding: 20px; width: 100%; max-width: 400px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); background: #fff; } h1 { font-size: 24px; margin-bottom: 20px; color: #007bff; } p { margin-bottom: 20px; font-size: 16px; color: #555; } button { width: 100%; padding: 15px; margin: 10px 0; font-size: 18px; font-weight: bold; color: #fff; border: none; border-radius: 6px; cursor: pointer; transition: background 0.3s; } .notify-btn { background: #28a745; } .notify-btn:hover { background: #218838; } .call-btn { background: #17a2b8; } .call-btn:hover { background: #138496; }

通知车主挪车
======

如需通知车主，请点击以下按钮

拨打车主电话

function callOwner() { window.location.href = "tel:13669027307"; //将xxx改成手机号码 }
