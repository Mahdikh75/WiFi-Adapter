# WiFi Adapter

WiFiAdapter Windows OS

    -------------------------
Code Simple for :

    public static WlanClient.WlanInterface Interface;

    public static Wlan.WlanAvailableNetwork[] AvNetwork;

    public static WlanClient client = new WlanClient();

    if (client.Interfaces.Length == 1)
    {
          Interface = client.Interfaces[0];
    }

    AvNetwork = Interface.GetAvailableNetworkList(Wlan.WlanGetAvailableNetworkFlags.IncludeAllManualHiddenProfiles);

    -------------------------
using the objects 'Interface' , 'AvNetwork' for app .....
