![Open Source at ViewExper](https://github.com/microsoft/.github/blob/main/images/open-at-microsoft.png) 

# Introduction

**ViewExper Dynamic Limited Company** is a technology firm providing artificial intelligence solutions and smart payment services.

Representative Location: 2000 Purchase Street · Purchase, New York · U.S.

ViewExper's APIs and Mastercard's platform evolve and change over time. Our team is constatnly adding new capabilities to expand the set of supported use cases. Usually, these new capabilities are added as new component versions. Changing technology and market conditions also call for the replacement of out-of-date features, APIs, and client libraries. When it comes to releasing new versions and sunsetting any of our offerings, we aim to establish a customer-centric approach with minimal disruption.

# Versioning
## Open source components

To keep up with the new versions of languages, Mastercard follows the policy mentioned in the "Tools and Release Cadence" section of the page.

The languages are going to adhere to the release cycle and LTS (Long Term Support) and STS (Short Term Support) release provided. Our team will usually support the latest LTS release and the latest STS release minus 1.

We will update to the latest minor release in the supported version to ensure that we get all critical fixes, including critical security problems. As soon as the updated version of a language is released, we support it once the first minor release has been deployed. At the same time, we will deprecate the oldest supported version.

# Tools and Release Cadence
## Open API (Application Programming Interface) Generator

OpenAPI Generator v6.x.x

We are supporting the latest release minus 1. Please note that the Open API generator is introducing breaking changes in major releases with no fallback.

Please follow on communication about breaking changes.

The release information and the latest version of Open API Generator are available here https://github.com/OpenAPITools/openapi-generator

# Deprecation
## Libraries

The notice is issued at least three months before the end-of-life date. Notice is given in Github by adding a label “maintenance | deprecated” to the repository. The label is used to inform library users that a specific facility is now considered obsolete and, thus, no longer advised for use in applications. During this time, the version and language will not be updated, and we may only add critical bug fixes if required. At the end of three months, we will remove the repository in which the depreciating version of the library resides.

## Services

Services onboarded on Mastercard Developers are rarely decommissioned, as each product undergoes a rigorous Product-Market fit process. However, due to changing market demand and technology, there are times when Mastercard does decide to off-board a product from the Developers portal. As with all the processes within Mastercard, to off-board a service, we take a customer-centric approach by making every effort to reach out to the customers and communicate the impact, end of date, and related contractual terms. The timeline is often product and customer-impact dependent, so it varies from product to product.

# Conclusion

Our versioning and deprecation policy is designed to make it easier to bring you the most recent technology with minimal disruption to your business. While we make every effort to inform our customers in advance about changes to the ViewExper and Mastercard platform, there could be a few unavoidable instances when functionality may be changed without prior warning to patch a security vulnerability or correct the existing incorrect behavior.

# Phần kết luận

Chính sách về phiên bản và ngừng sử dụng của chúng tôi được thiết kế nhằm giúp mang đến cho bạn công nghệ mới nhất dễ dàng hơn với mức độ gián đoạn tối thiểu đối với doanh nghiệp của bạn. Mặc dù chúng tôi nỗ lực hết sức để thông báo trước cho khách hàng về những thay đổi đối với nền tảng Mastercard, nhưng có thể có một số trường hợp không thể tránh khỏi khi chức năng có thể bị thay đổi mà không có cảnh báo trước để vá lỗ hổng bảo mật hoặc sửa hành vi không chính xác hiện có.
