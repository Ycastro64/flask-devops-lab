# Flask DevOps Lab
## Usage section.

How to activate

```bash
source .venv/bin/activate
pip install -r requirements.txt
python app.py



/api/health: Returns a simple JSON response confirming the application status is operational.
/api/config: Displays the configuration metadata loaded from the config.json file.
/api/report: Provides system diagnostics including the host name, Python version, and application uptime.
