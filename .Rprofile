# Ne jamais activer renv en CI / GitHub Actions
if (identical(Sys.getenv("CI"), "true") || nzchar(Sys.getenv("GITHUB_ACTIONS"))) {
  # rien
} else {
  if (file.exists("renv/activate.R")) source("renv/activate.R")
}
