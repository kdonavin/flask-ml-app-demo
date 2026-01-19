release: python src/create_db.py && python src/build_model.py --data data/articles.csv --out static/model.pkl
web: gunicorn app:app