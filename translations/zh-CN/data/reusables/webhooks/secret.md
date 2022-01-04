设置 web 挂钩密钥使您可以确保将 `POST` 请求发送到来自 {% data variables.product.product_name %} 的有效负载 URL。 When you set a secret, you'll receive the {% ifversion fpt or ghes or ghec %}`X-Hub-Signature` and `X-Hub-Signature-256` headers{% elsif ghae %}`X-Hub-Signature-256` header{% endif %} in the webhook `POST` request. 有关如何使用密钥和签名标头来保护 web 挂钩有效负载的更多信息，请参阅“[保护 web 挂钩](/webhooks/securing/)”。