---
menu: main
weight: 4
title: "Contact us"
description: "為 *老年化社會* 的 **健康** 和 **福祉** 而設的 綜合平台"
hero_images: ["/images/banner.png"]
---
{{< bulma/tile modifiers="is-ancester" >}}
  {{< bulma/tile modifiers="is-parent" >}}
    {{< bulma/tile modifiers="is-child box content is-medium" markkdown="true" >}}
      
    {{< /bulma/tile >}}
  {{< /bulma/tile >}}
{{< /bulma/tile >}}

{{< bulma/tile modifiers="is-ancester" >}}
  {{< bulma/tile modifiers="is-parent is-3" >}}
    {{< bulma/tile modifiers="is-child box" >}}
      {{< bulma/image image_src="/images/contact_us.png" modifiers="is-fullwidth" >}}
    {{< /bulma/tile >}}
  {{< /bulma/tile >}}
  {{< bulma/tile modifiers="is-parent" >}}
    {{< bulma/tile modifiers="is-child box content is-medium" markkdown="true" >}}
      <form action="https://script.google.com/macros/s/AKfycbzMQNMqnIv1dXPj-7CsHgcTjryAlm79bJpaiIvmryvY1zGPkVA9/exec" method="POST" accept-charset="UTF-8">
        <div class="field">
          <label class="label">姓名 *</label>
          <div class="control">
            <input class="input" type="text" name="name" placeholder="請填寫你的 姓名" >
          </div>
        </div>
        <div class="field">
          <label class="label">電郵 *</label>
          <div class="control">
            <input class="input" type="text" name="email" placeholder="請填寫你的 電郵">
          </div>
        </div>
        <div class="field">
          <label class="label">聯絡電話</label>
          <div class="control">
            <input class="input" type="text" name="phone_no" placeholder="請填寫你的 聯絡電話">
          </div>
        </div>
        <div class="field">
          <label class="label">訊息內容 *</label>
          <div class="control">
            <textarea class="textarea" name="message" placeholder="訊息內容"></textarea>
          </div>
        </div>
        <div class="control">
          <button class="button is-link">發出</button>
        </div>
      </form>

    {{< /bulma/tile >}}
  {{< /bulma/tile >}}
{{< /bulma/tile >}}
