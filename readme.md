# Dataset and Competitions
    \textit{https://www.kaggle.com/competitions/ristek-datathon-2022}
# Columns
   * id          -> unique
   * created_at  -> timestamp
   * user_id     -> pengupload, nunique, 1169 77% unique
   * user_name   -> pengupload, nunique, 1168 77% unique
    // user_id tidak bijektif terhadap user_name
   * url         -> url dari tweet
   * text        -> isi text dari tweet
   * media       -> nama file .jpg yang ada pada data yang diberikan
   * label       -> target variable, apakah perlu action (1) atau tidak (0)
# DECISION:
   * id          drop
   * url         drop
   * user_id     drop
[TODO] CONTINUE DOCUMENTATION 
