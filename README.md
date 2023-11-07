# Honeypots Detection
Nuclei templates for honeypots detection.

This repository contains Nuclei templates to detect several well-known open-source honeypots, such as: ADBHoney, Conpot, Cowrie, Dionaea (multiple services), ElasticPot, Mailoney, Redis Honeypot, Snare, among others.

## Usage

1. Install Nuclei (https://github.com/projectdiscovery/nuclei#install-nuclei).
2. Clone this repository:  
   `git clone https://github.com/UnaPibaGeek/honeypots-detection.git`
3. Move into the templates folder:  
   `cd honeypots-detection/templates`
4. Run the desired template as follows:  
   `sudo nuclei -u {target_IP} -t ./{template_name}.yaml`

## Example

![example](https://github.com/UnaPibaGeek/honeypots-detection/blob/main/examples/example.png)

For a more detailed output it is possible to use the `-debug-resp` parameter:

![example_debug](https://github.com/UnaPibaGeek/honeypots-detection/blob/main/examples/example_debug.png)

The requests will be sent to the honeypot's default port if not specified.

## Acknowledgements
- Thank you [Project Discovery](https://github.com/projectdiscovery/nuclei) for such a great tool and contribution to our community.
- These templates were developed while researching honeypots at [Dreamlab Technologies](www.dreamlab.net) for [CYOBS](www.cyobs.com).

Made with ❤️ by [UnaPibaGeek](https://www.twitter.com/UnaPibaGeek).
