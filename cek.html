<?php

$tracking_number = "SPXID123456789"; // Ganti dengan nomor resi
$access_token    = "YOUR_ACCESS_TOKEN"; // Token dari Shopee API
$shop_id         = "YOUR_SHOP_ID";

$url = "https://partner.shopeemobile.com/api/v2/logistics/get_tracking_info";

$data = [
    "shop_id" => (int)$shop_id,
    "tracking_number" => $tracking_number
];

$headers = [
    "Content-Type: application/json",
    "Authorization: Bearer " . $access_token
];

$ch = curl_init($url);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
curl_setopt($ch, CURLOPT_POST, true);
curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode($data));
curl_setopt($ch, CURLOPT_HTTPHEADER, $headers);

$response = curl_exec($ch);

if (curl_errno($ch)) {
    echo 'Error:' . curl_error($ch);
} else {
    $result = json_decode($response, true);

    echo "<h3>Tracking Info:</h3>";
    echo "<pre>";
    print_r($result);
    echo "</pre>";

    // Contoh ambil no HP penerima (jika tersedia di response)
    if(isset($result['response']['recipient']['phone'])) {
        echo "No HP Penerima: " . $result['response']['recipient']['phone'];
    } else {
        echo "No HP tidak tersedia atau tidak diizinkan.";
    }
}

curl_close($ch);

?>
