# soc-investigation-portfolio
A hands-on SOC analyst portfolio documenting security alert triage, log analysis, threat investigation, detection logic, and incident response.
# Create directories
mkdir -p investigations/01-suspicious-login
mkdir -p investigations/02-phishing
mkdir -p detection-rules
mkdir -p screenshots

# Create placeholder README files
touch investigations/01-suspicious-login/README.md
touch investigations/02-phishing/README.md
touch detection-rules/.gitkeep
touch screenshots/.gitkeep

# Commit and push
git add .
git commit -m "Add project folder structure"
git push
