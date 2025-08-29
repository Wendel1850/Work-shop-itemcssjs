import React from 'react';
import WorkshopItem from './WorkshopItem';

const Workshops = () => {
  return (
    <div>
      <WorkshopItem
        title="Workshop de Desenvolvimento Web"
        description="Aprenda a criar aplicações web modernas com HTML, CSS e JavaScript."
        date="2023-03-15"
        time="10:00"
        location="São Paulo"
      />
      <WorkshopItem
        title="Workshop de Design Gráfico"
        description="Aprenda a criar designs gráficos atraentes com Adobe Photoshop e Illustrator."
        date="2023-04-20"
        time="14:00"
        location="Rio de Janeiro"
      />
    </div>
  );
};




.workshop-item {
  background-color: #f7f7f7;
  padding: 20px;
  border: 1px solid #ddd;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.workshop-item h2 {
  font-size: 18px;
  font-weight: bold;
  margin-bottom: 10px;
}

.workshop-item p {
  font-size: 14px;
  color: #666;
}

.workshop-details {
  margin-top: 20px;
}

.workshop-details p {
  font-size: 14px;
  color: #666;
}
