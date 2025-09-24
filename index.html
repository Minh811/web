CODE ĐỔI TÊN ICON BY FB.COM/VANDUC.SG

javascript:(() => { 
  const uid2 = prompt("NGUỒN: fb.com/vanduc.sg| NHẬP ID INSTAGRAM:");

  function generateClientMutationId() {
    return ([1e7]+-1e3+-4e3+-8e3+-1e11).replace(/[018]/g, c =>
      (c ^ crypto.getRandomValues(new Uint8Array(1))[0] & 15 >> c / 4).toString(16)
    );
  }

  try {
    const dtsg = require("DTSGInitData").token;
    const userid = require("CurrentUserInitialData").USER_ID;

    const url = 'https://accountscenter.facebook.com/api/graphql/';
    const clientMutationId = generateClientMutationId();

    const variables = {
      client_mutation_id: clientMutationId,
      accounts_to_sync: [uid2, userid],
      resources_to_sync: ["NAME", "PROFILE_PHOTO"],
      resources_to_unsync: null,
      scale: 3,
      source_of_truth_array: [{ resource_source: "IG" }, { resource_source: "FB" }],
      source_account: userid,
      family_device_id: "device_id_fetch_datr",
      username_unsync_params: null,
      platform: "FACEBOOK",
      sync_logging_params: { client_flow_type: "IM_SETTINGS" },
      interface: "FB_WEB",
      feta_profile_sync: false
    };

    const data = `fb_dtsg=${encodeURIComponent(dtsg)}&__user=${userid}&variables=${encodeURIComponent(JSON.stringify(variables))}&av=${userid}&fb_api_req_friendly_name=useFXIMUpdateNameMutation&fb_api_caller_class=RelayModern&server_timestamps=true&doc_id=9388416374608398`;

    fetch(url, {
      method: 'POST',
      body: data,
      headers: {
        'Content-Type': 'application/x-www-form-urlencoded'
      }
    })
    .then(resp => resp.json())
    .then(resp => {
      if (resp.errors || resp.error) {
        console.error("Lỗi từ Facebook:", resp);
        alert("Không thành công: " + (resp.errors?.[0]?.message || resp.error?.message || "Lỗi không xác định"));
      } else {
        alert("Gửi yêu cầu thành công (Facebook có thể vẫn từ chối ở backend)");
      }
    })
    .catch(err => {
      console.error("Lỗi khi gửi yêu cầu:", err);
      alert("Lỗi kết nối: " + err.message);
    });

  } catch (e) {
    alert("Không thể lấy token. Hãy chắc chắn bạn đang mở trang Facebook.");
  }
})();
