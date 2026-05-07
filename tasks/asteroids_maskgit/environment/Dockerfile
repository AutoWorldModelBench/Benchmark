FROM autoworldbench-base:latest

# Nest task files so run.py's REPO_ROOT (TASK_DIR.parent.parent) = /app/ (writable)
COPY --chown=agent:agent train.py run.py config.json config_template.json score.py /app/tasks/asteroids_maskgit/

WORKDIR /app/tasks/asteroids_maskgit
