---
-api-id: P:Windows.UI.Xaml.Controls.WebViewPermissionRequest.Id
-api-type: winrt property
---

<!-- Property syntax
public uint Id { get; }
-->

# Windows.UI.Xaml.Controls.WebViewPermissionRequest.Id

## -description
Gets the identifier for the permission request.

## -property-value
The identifier for the permission request.

## -remarks
If you defer a permission request, save the [Id](webviewpermissionrequest_id.md) to use later to retrieve the deferred request.

When a [WebViewPermissionRequest](webviewpermissionrequest.md) is deferred, a [WebViewDeferredPermissionRequest](webviewdeferredpermissionrequest.md) is created with the same [Id](webviewpermissionrequest_id.md) and added to the [DeferredPermissionRequests](webview_deferredpermissionrequests.md) collection. When you are ready to act on the request, call the [DeferredPermissionRequestById](webview_deferredpermissionrequestbyid.md) method and pass the [Id](webviewdeferredpermissionrequest_id.md) of the deferred request.

## -examples

## -see-also