# teensy3-piggyback
Piggyback board for a Teensy 3 that holds a MicroSD and a LIPO charger
The LIPO charger needs the connector pads on the Teensy opened to run off battery
The switch allows you to switch from battery supply to USB supply or (central position) off.
The LED shows if it is charging or not.
Pin 14/AO can be queried for a current battery voltage. It is not accurate but it is to scale.
The button on the Teensy is covered by the piggy back board, unless you mount it underneath instead of on top. So the button is replicated on the piggy back.
Developed for Teensy 3.0 but the pins on later Teensys look compatible.
Be aware than the pins on the end opposite the USB are not breadboard friendly (like the pins on the Tennsy). If you solder them in place you won't be able to plug into a breadboard unless you trim the ends of those pins down so they don't plug into your breadboard. The side pins can remain as they are and they will work fine with your breadboard.

<a href="https://www.oshpark.com/shared_projects/XkRxbt6A"><img src="https://a800d827b6de8403a51e-6ffc2e718631809086ea40332b2055f7.ssl.cf1.rackcdn.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>

